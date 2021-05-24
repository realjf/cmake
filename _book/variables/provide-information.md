## 提供信息变量

- CMAKE_AR 静态库归档工具的名称。这指定了创建档案库或静态库的程序的名称。
- CMAKE_ARGC 在脚本模式下传递给CMake的命令行参数的数量。
- CMAKE_ARGVO 命令行参数以脚本模式传递给CMake
- CMAKE_BINARY_DIR 到构建树顶层的路径。这是当前CMake构建树顶层的完整路径。对于源内构建，这将与CMAKE_SOURCE_DIR相同。
- CMAKE_BUILD_TOOL 仅存在此变量是为了向后兼容。它包含与CMAKE_MAKE_PROGRAM相同的值。请改用该变量。
- CMAKE_CACHE_MAJOR_VERSION 用于创建CMakeCache.txt文件的CMake的主要版本
- CMAKE_CACHE_MINOR_VERSION 用于创建CMakeCache.txt文件的CMake的次要版本
- CMAKE_CACHE_PATCH_VERSION 用于创建CMakeCache.txt文件的CMake修补程序版本
- CMAKE_CACHEFILE_DIR 带有CMakeCache.txt文件的目录。这是其中包含CMakeCache.txt文件的目录的完整路径。这与CMAKE_BINARY_DIR相同。
- CMAKE_CFG_INTDIR  对每个配置的输出子目录的构建时参考。
- CMAKE_COMMAND  cmake可执行文件的完整路径
- CMAKE_CPACK_COMMAND CMake安装的cpack（1）命令的完整路径。
- CMAKE_CROSSCOMPILING 旨在指示CMake是否交叉编译
- CMAKE_CROSSCOMPILING_EMULATOR 仅当CMAKE_CROSSCOMPILING启用时，才使用此变量。它应该指向主机系统上的命令，该命令可以运行为目标系统构建的可执行文件。
- CMAKE_CTEST_COMMAND  CMake安装的ctest（1）命令的完整路径。
- CMAKE_CURRENT_BINARY_DIR  当前正在处理的二进制目录的路径。