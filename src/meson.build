unibenchmark_sources = [
  'main.c',
  'unibenchmark-application.c',
  'unibenchmark-window.c',
]

unibenchmark_deps = [
  dependency('gtk4'),
]

unibenchmark_sources += gnome.compile_resources('unibenchmark-resources',
  'unibenchmark.gresource.xml',
  c_name: 'unibenchmark'
)

executable('unibenchmark', unibenchmark_sources,
  dependencies: unibenchmark_deps,
       install: true,
)
