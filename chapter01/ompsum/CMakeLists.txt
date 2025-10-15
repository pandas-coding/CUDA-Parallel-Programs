add_executable(chapter01-ompsum ompsum.cpp)

target_include_directories(chapter01-ompsum
        PRIVATE
        ${PROJECT_SOURCE_DIR}/shared
)

target_link_libraries(chapter01-ompsum PRIVATE shared)

