add_executable(chapter02-gupsum-tla gpusum_tla.cu)

target_link_directories(chapter02-gupsum-tla
    PRIVATE
        ${PROJECT_SOURCE_DIR}/shared
)

target_link_libraries(chapter02-gupsum-tla
    PRIVATE
        shared
)
