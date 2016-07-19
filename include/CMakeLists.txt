set(install_headers
    enet/enet.h
    enet/callbacks.h
    enet/list.h
    enet/protocol.h
    enet/types.h
    enet/unix.h
    enet/win32.h
)

set(headers ${install_headers} 
    enet/time.h
    enet/utility.h
)
install(
  FILES ${install_headers}
  DESTINATION include/enet
)
