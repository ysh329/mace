add_library(port_linux_base STATIC
  env.cc
)

target_link_libraries(port_linux_base port_posix)
