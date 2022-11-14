project('malloc_count', 'c',
  license: 'MIT')

malloc_count = library('malloc_count', 'malloc_count.c')

malloc_count_dep = declare_dependency(
  include_directories: include_directories('.'),
  sources: 'malloc_count.c',
  link_with: malloc_count
)


