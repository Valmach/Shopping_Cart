cmake_minimum_required(VERSION 3.7)
project(Shopping_Cart)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        amazon.cpp
        book.cpp
        book.h
        bst.h
        clothing.cpp
        clothing.h
        datafunction.cpp
        datafunction.h
        datastore.h
        db_parser.cpp
        db_parser.h
        login_window.cpp
        login_window.h
        main_window.cpp
        main_window.h
        movie.cpp
        movie.h
        msort.h
        product.cpp
        product.h
        product_parser.cpp
        product_parser.h
        review.h
        splay_tree.h
        user.cpp
        user.h
        util.cpp
        util.h)

add_executable(Shopping_Cart ${SOURCE_FILES})