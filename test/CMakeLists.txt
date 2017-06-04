
add_executable(
    testkata
    gtest_main.cpp
    KataTest.cpp
)

target_link_libraries(
    testkata
    libgtest
    libgmock
)
