load('//:buckaroo_macros.bzl', 'buckaroo_deps')
load('//:subdir_glob.bzl', 'subdir_glob')

cxx_library(
  name = 'fixmath',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('', 'libfixmath/**/*.hpp'),
    ('', 'libfixmath/**/*.h'),
  ]),
  srcs = glob([
    'libfixmath/**/*.c',
  ]),
  deps = buckaroo_deps(),
  visibility = [
    'PUBLIC',
  ],
)
