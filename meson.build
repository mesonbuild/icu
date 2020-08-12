project('icu', 'c', 'cpp',
  version: '55.2',
  meson_version: '>=0.55.0',
  default_options: 'cpp_std=c++11')

add_project_arguments('-DU_USING_ICU_NAMESPACE=0', language : 'cpp')

dl_dep = meson.get_compiler('cpp').find_library('dl', required: false)
thread_dep = dependency('threads')

if get_option('default_library') == 'static'
  add_project_arguments('-DU_STATIC_IMPLEMENTATION', language : 'c')
  add_project_arguments('-DU_STATIC_IMPLEMENTATION', language : 'cpp')
endif

subdir('source')
