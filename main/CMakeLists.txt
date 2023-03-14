add_executable(picoTemplateProject main.c)

# pull in common dependencies
target_link_libraries(picoTemplateProject pico_stdlib)

# create map/bin/hex file etc.
pico_add_extra_outputs(picoTemplateProject)
