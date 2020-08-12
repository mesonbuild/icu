sources = files('ParagraphLayout.cpp',
  'RunArrays.cpp',
  'LXUtilities.cpp',
  'playout.cpp',
  'plruns.cpp',
)

layoutex = library('layoutex',
  sources,
  include_directories : [incdir, include_directories('..')],
  link_with: [layout_lib, common_lib],
)
