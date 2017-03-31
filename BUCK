include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'interprocess',
  header_only = True,
  header_namespace = 'boost/interprocess',
  exported_headers = subdir_glob([
    ('include/boost/interprocess', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
