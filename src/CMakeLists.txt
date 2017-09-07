set(SRCS
        main.cpp
    )

set(HEADERS

    )

add_executable(ipt ${SRCS} ${HEADERS})

target_link_libraries(ipt ${OpenCV_LIBS})
