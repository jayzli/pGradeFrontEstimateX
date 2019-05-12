#--------------------------------------------------------
# The CMakeLists.txt for:                  pGradeFrontEstimateX
# Author(s):                              
#--------------------------------------------------------

# FILE(GLOB SRC *.cpp)

SET(SRC
  GradeFrontEstimate.cpp
  GradeFrontEstimate_Info.cpp
  main.cpp
)



ADD_EXECUTABLE(pGradeFrontEstimateX ${SRC})

TARGET_LINK_LIBRARIES(pGradeFrontEstimateX
   ${MOOS_LIBRARIES}
   mbutil
   m
   pthread)

