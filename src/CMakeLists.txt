if(NOT SLLVM_INSTALL_DIR)
  add_subdirectory(llvm)
  add_subdirectory(stubs)
endif()
add_subdirectory(drivers)
add_subdirectory(sancus_support)
add_subdirectory(crypto)
