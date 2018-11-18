include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'gil', 
  header_namespace = 'boost', 
  header_only = True, 
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'), 
  ]), 
  deps = BUCKAROO_DEPS, 
  visibility = [
    'PUBLIC', 
  ], 
)
