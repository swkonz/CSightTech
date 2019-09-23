## CSight Technologies
An OpenCV based single webcam assistive system for mouse control using only eye movements. Eye tracking is based on simple image gradient eye center algorithm by Fabian Timm.

## Status
This Project was combined with an EEG trigger to add button-press functionality and formed the basis for the US patent application `us 15268543`

### OSX or Linux with Make
```bash
# do things in the build directory so that we don't clog up the main directory
mkdir build
cd build
cmake ../
make
./bin/eyeLike # the executable file
```
