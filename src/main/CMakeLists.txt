aux_source_directory(. SRCS)
add_executable(live ${SRCS})

install(TARGETS live RUNTIME DESTINATION sbin)