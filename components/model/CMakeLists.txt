idf_component_register(SRCS "model.c"
                    INCLUDE_DIRS "include" "../open62541lib/include"
                    REQUIRES "driver" "dht")
component_compile_options(-Wno-error=format= -Wno-format)