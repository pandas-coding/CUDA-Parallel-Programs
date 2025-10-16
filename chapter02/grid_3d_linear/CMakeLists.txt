add_executable(chapter02-grid-3d-linear grid_3d_linear.cu)

target_link_directories(chapter02-grid-3d-linear
    PRIVATE
        ${PROJECT_SOURCE_DIR}/shared
)

target_link_libraries(chapter02-grid-3d-linear
    PRIVATE
        shared
)
