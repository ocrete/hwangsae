sources = [
  'test.c',
  'test-streamer.c',
]

libhwangsae_test_common = library(
  'hwangsae-test-common',
  sources,
  dependencies: [ glib_dep, gaeguli_dep, gstreamer_pbutils_dep ],
  c_args: test_c_args,
  install: false
)
