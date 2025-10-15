add_executable(chapter01-cpusum cpusum.cpp)

target_include_directories(chapter01-cpusum PRIVATE ${PROJECT_SOURCE_DIR}/shared)

target_link_libraries(chapter01-cpusum PRIVATE shared)
