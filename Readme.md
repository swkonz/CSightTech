## Assistive Tech code
An OpenCV based webcam gaze tracker based on a simple image gradient-based eye center algorithm by Fabian Timm.

The code in this repo is originally from the EyeLike repo, and changes have been made to it in order to trigger on certain eye movements.

Original Code here: https://github.com/trishume/eyeLike


## Status
This repo is meant more as an archive of this code since it was so long ago. This hasn't been tested in some time and is likely breaking.

### OSX or Linux with Make
```bash
# do things in the build directory so that we don't clog up the main directory
mkdir build
cd build
cmake ../
make
./bin/eyeLike # the executable file
```
