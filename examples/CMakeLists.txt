cmake_minimum_required(VERSION 3.14)

add_executable(basic_app basic_app.cpp)
target_link_libraries(basic_app PUBLIC orni::orni)

add_executable(custom_error_page custom_error_page.cpp)
target_link_libraries(custom_error_page PUBLIC orni::orni)

add_executable(query_example query_example.cpp)
target_link_libraries(query_example PUBLIC orni::orni)

add_executable(redirect_page redirect_page.cpp)
target_link_libraries(redirect_page PUBLIC orni::orni)

add_executable(basic_auth basic_auth.cpp)
target_link_libraries(basic_auth PUBLIC orni::orni)

add_executable(rest_api rest_api.cpp)
target_link_libraries(rest_api PUBLIC orni::orni)

add_executable(template_example template_example.cpp)
target_link_libraries(template_example PUBLIC orni::orni)
