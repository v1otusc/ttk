ttk_add_vtk_library(ttkJacobiSet
  SOURCES
    ttkJacobiSet.cpp
  HEADERS
    ttkJacobiSet.h
  LINK
    jacobiSet
    ttkTriangulation
    )
