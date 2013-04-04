file(GLOB Game_HEADERS "*.h")
file(GLOB Game_SOURCES "*.cpp")

add_executable(Game ${Game_SOURCES} ${Game_HEADERS})
