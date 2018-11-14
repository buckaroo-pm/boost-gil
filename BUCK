prebuilt_cxx_library(
  name = 'gil', 
  header_namespace = 'boost', 
  header_only = True, 
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'), 
  ]), 
  deps = [
    'buckaroo.github.buckaroo-pm.boost-config//:config', 
    'buckaroo.github.buckaroo-pm.boost-bind//:bind', 
    'buckaroo.github.buckaroo-pm.boost-concept_check//:concept-check', 
    'buckaroo.github.buckaroo-pm.boost-integer//:integer', 
    'buckaroo.github.buckaroo-pm.boost-iterator//:iterator', 
    'buckaroo.github.buckaroo-pm.boost-mpl//:mpl', 
    'buckaroo.github.buckaroo-pm.boost-numeric_conversion//:numeric-conversion', 
    'buckaroo.github.buckaroo-pm.boost-static_assert//:static-assert', 
    'buckaroo.github.buckaroo-pm.boost-utility//:utility', 
    'buckaroo.github.buckaroo-pm.libjpeg-turbo//:jpeg-turbo'
  ], 
  visibility = [
    'PUBLIC', 
  ], 
)
