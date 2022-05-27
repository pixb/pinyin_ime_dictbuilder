cmake_minimum_required(VERSION 3.23)
project(pinyin_ime_dictbuilder)

set(CMAKE_CXX_STANDARD 11)


add_executable(pinyin_ime_dictbuilder
        pinyinime_dictbuilder.cpp
        share/dictbuilder.cpp
        share/dictlist.cpp
        share/dicttrie.cpp
        share/lpicache.cpp
        share/mystdlib.cpp
        share/ngram.cpp
        share/searchutility.cpp
        share/spellingtable.cpp
        share/spellingtrie.cpp
        share/splparser.cpp
        share/utf16char.cpp
        share/utf16reader.cpp
        )