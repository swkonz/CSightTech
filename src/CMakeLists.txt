#find_library(MGL mgl PATHS /usr/local/lib)

ADD_EXECUTABLE( csight main.cpp findEyeCenter.cpp findEyeCenter.h findEyeCorner.cpp findEyeCorner.h constants.h helpers.cpp helpers.h)
TARGET_LINK_LIBRARIES( csight ${OpenCV_LIBS} )
#target_link_libraries( csight ${MGL})