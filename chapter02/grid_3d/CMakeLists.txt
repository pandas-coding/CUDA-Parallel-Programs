add_executable(chapter02-grid-3d grid_3d.cu)

target_link_directories(chapter02-grid-3d
    PRIVATE
        ${PROJECT_SOURCE_DIR}/shared
)

target_link_libraries(chapter02-grid-3d
    PRIVATE
        shared
)
