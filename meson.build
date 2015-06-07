project('icu', 'c', 'cpp')

add_global_arguments('-DU_USING_ICU_NAMESPACE=0', language : 'cpp')

if get_option('shared_lib')
  libtype = 'shared_library'
else
  add_global_arguments('-DU_STATIC_IMPLEMENTATION', language : 'c')
  add_global_arguments('-DU_STATIC_IMPLEMENTATION', language : 'cpp')
  libtype = 'static_library'
endif

subdir('source')
