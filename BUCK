cxx_library(
  name = 'angelscript',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('sdk/angelscript/include', '*.h'),
  ]),
  headers = subdir_glob([
    ('sdk/angelscript/source', '*.h'),
  ]),
  srcs = glob([
    'sdk/angelscript/source/*.cpp',
  ]),
  compiler_flags = [
    '-std=c++11',
    '-DMAXUINT64=18446744073709551615',
  ],
  visibility = [
    'PUBLIC',
  ],
)
