add_executable(FittedBondCurve FittedBondCurve.cpp)
target_link_libraries(FittedBondCurve ql_library ${QL_EXAMPLES_LIBRARIES})
if (QL_INSTALL_EXAMPLES)
    install(TARGETS FittedBondCurve RUNTIME DESTINATION ${QL_INSTALL_EXAMPLESDIR})
endif()
