CU_SET_PATH("CMAKE_MOD_CUSTOMSERVER_DIR" "${CMAKE_CURRENT_LIST_DIR}")

AC_ADD_SCRIPT("${CMAKE_CURRENT_LIST_DIR}/src/mod_customserver.cpp")

AC_ADD_SCRIPT_LOADER("CustomServer" "${CMAKE_CURRENT_LIST_DIR}/src/loader_customserver.h")

AC_ADD_CONFIG_FILE("${CMAKE_CURRENT_LIST_DIR}/conf/mod_customserver.conf.dist")
