cmake_minimum_required(VERSION 3.10)

include_directories(/usr/include/panda3d)
link_directories(/usr/lib/x86_64-linux-gnu/panda3d)

add_executable(main main.cc)
target_link_libraries(main p3framework pthread panda pandafx pandaexpress p3dtoolconfig p3dtool p3direct)