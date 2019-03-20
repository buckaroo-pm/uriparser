load('//:subdir_glob.bzl', 'subdir_glob')

cxx_library(
  name = 'uriparser',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('include', '**/*.h'),
  ]),
  headers = subdir_glob([
    ('src', '**/*.h'),
  ]),
  srcs = glob([
    'src/**/*.c',
  ]),
  licenses = [
    'COPYING',
  ],
  visibility = [
    'PUBLIC',
  ],
)
