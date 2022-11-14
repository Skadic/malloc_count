project('malloc_count', 'c',
  license: 'MIT')

malloc_count_lib = library('malloc_count', 'malloc_count.c')

malloc_count = declare_dependency('malloc_count',
  include_directories: include_directories('.'),
  sources: 'malloc_count.c',
  link_with: malloc_count_lib
)


