add_subdirectory(default)


if(${OCKAM_BUILD_TESTS})
  add_subdirectory(tests)
endif()
