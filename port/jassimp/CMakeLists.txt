#@author Юрин Роман
#@date 14.03.2018
#Модуль с JNI классами для интеграции с JAVA
add_library(JAssimp ${CMAKE_CURRENT_SOURCE_DIR}/jassimp-native/src/jassimp.h ${CMAKE_CURRENT_SOURCE_DIR}/jassimp-native/src/jassimp.cpp)
