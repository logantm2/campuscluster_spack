# campuscluster_spack

Scripts for installing modules useful for LCPP codes and developers on the Illinois Campus Cluster with Spack.

Usage:
```bash
mkdir share && cd share
git clone git@github.com:logantm2/campuscluster_spack.git
cd campuscluster_spack
. setup.sh
```
This will download Spack and then use Spack to install a bunch of packages,
which are then added to the module list.

After running, it is useful to add the Spack source command to your `.bashrc`:

`. /path/to/share/spack/share/spack/setup-env.sh`

Also suggest making the `share` directory at least read-accessible by the group.
