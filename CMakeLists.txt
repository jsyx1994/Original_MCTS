cmake_minimum_required(VERSION 3.15)
project(Original_MCTS)

set(CMAKE_CXX_STANDARD 14)

include_directories("Original MCTS/jsoncpp")

add_executable(Original_MCTS
        "Original MCTS/jsoncpp/json-forwards.h"
        "Original MCTS/jsoncpp/json.h"
        "Original MCTS/EMCTS.cpp"
        "Original MCTS/jsoncpp.cpp"
        "Original MCTS/MCTS.cpp")
