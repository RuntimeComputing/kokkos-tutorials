cmake_minimum_required (VERSION 3.10)
project (KokkosKernelsCGSolve)
include(../../common.cmake)

add_executable(cgsolve cgsolve.cpp)
target_link_libraries(cgsolve Kokkos::kokkoskernels)


