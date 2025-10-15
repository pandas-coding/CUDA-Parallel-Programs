cmake_minimum_required(VERSION 3.23)
project(cuda_practice_programs LANGUAGES CXX CUDA)

# 统一标准设置（主机/设备）
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CUDA_STANDARD 20)
set(CMAKE_CUDA_STANDARD_REQUIRED ON)

# 注册共享模块与章节子项目
add_subdirectory(shared)
add_subdirectory(chapter01)
add_subdirectory(chapter02)

# 示例：根级别单独可执行（可选）
add_executable(main-app main.cu)
target_link_libraries(main-app PRIVATE shared)



