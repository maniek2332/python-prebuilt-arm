cmake_minimum_required(VERSION 3.0)

install(FILES lib/libpython3.6m.so DESTINATION lib)
install(DIRECTORY include/python3.6m DESTINATION include)
install(DIRECTORY lib/python3.6 DESTINATION lib)
