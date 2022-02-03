cmake_minimum_required(VERSION 3.21)
project(UDP_Server_Client C)

set(CMAKE_C_STANDARD 99)

add_executable(UDP_Server UDP_Server.c)
add_executable(UDP_Client UDP_Client.c)
add_executable(DENM_CAM_Message DENM_CAM_Message.c)
