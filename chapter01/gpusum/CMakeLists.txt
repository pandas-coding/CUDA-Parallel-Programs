add_executable(chapter01-gpusum gpusum.cu)

target_include_directories(chapter01-gpusum
    PRIVATE
        ${PROJECT_SOURCE_DIR}/shared
)

target_link_libraries(chapter01-gpusum
    PRIVATE
        shared
)
