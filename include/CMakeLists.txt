set(install_headers
    enet/callbacks.h
    enet/enet.h
    enet/list.h
    enet/protocol.h
    enet/time.h
    enet/types.h
    enet/unix.h
    enet/utility.h
    enet/win32.h
)


install(
  FILES ${install_headers}
  DESTINATION include/enet
)
