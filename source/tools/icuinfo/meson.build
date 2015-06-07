# This is not really needed to run icuinfo and
# there are some complications. If you wish to
# debug it, uncomment and have fun.

#shared_library('plugin', 'testplug.c',
#  include_directories : [incdir, toolinc],
#  link_with : [toolutil, i18n, common, stubdata],
#)


executable('icuinfo', 'icuinfo.cpp',
  include_directories : [incdir, toolinc],
  link_with : [toolutil, i18n, common, stubdata],
)
