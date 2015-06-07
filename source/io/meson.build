sources = [
  'locbund.cpp',
  'ufile.c',
  'ufmt_cmn.c',
  'uprintf.cpp',
  'uprntf_p.c',
  'uscanf.c',
  'uscanf_p.c',
  'ustdio.c',
  'sprintf.c',
  'sscanf.c',
  'ustream.cpp',
  'ucln_io.cpp',
]

io = build_target('io',
  sources,
  include_directories : incdir,
  c_args : '-DU_IO_IMPLEMENTATION',
  cpp_args : '-DU_IO_IMPLEMENTATION',
  target_type : libtype
)
