prebuilt_cxx_library(
  name = 'assimp',
  header_namespace = 'assimp',
  soname = 'libassimp.so.4',
  shared_lib = 'lib/libassimp.so',
  exported_headers = subdir_glob([
    ('include/assimp','**/*.h'),
    ('include/assimp','**/*.inl'),
    ('include/assimp','**/*.hpp'),
  ]),
  visibility = ['PUBLIC']
)


