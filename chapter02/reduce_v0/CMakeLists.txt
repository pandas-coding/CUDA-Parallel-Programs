add_executable(chapter02-reduce-v0 reduce_v0.cu)

target_link_directories(chapter02-reduce-v0
    PRIVATE
        ${PROJECT_SOURCE_DIR}/shared
)

target_link_libraries(chapter02-reduce-v0
    PRIVATE
        shared
)
