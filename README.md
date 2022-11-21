# container-pyseg

Install as a module share module using `shpc`.

```
# Install
cd /path/to/registry
git clone git@github.com:rosalindfranklininstitute/container-pyseg.git
shpc install pyseg

# Update
cd /path/to/registry/pyseg
git pull
shpc install pyseg

# Usage
module load pyseg

# Open pyseg GUI by running
pyseg

# Run commands against the container
pyseg-run which pyseg
# gives the path within the container to the install location
/usr/local/pyseg/bin/pyseg

# Print the module usage help
module help pyseg
```

This module aliases `pyseg` to `/usr/local/pyseg/bin/pyseg` within the container. 