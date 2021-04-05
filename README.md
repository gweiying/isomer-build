## Isomer Build Repo

This repo contains the files required for the Isomer build process.


### Build script
The `build.sh` script generates the build command with directory paths `_folder/collection.yml`, and takes the option `-e` for Jekyll build environment. The environment defaults to production.  

For staging, run `bash build.sh -e staging`. For production, run `bash build.sh`.
