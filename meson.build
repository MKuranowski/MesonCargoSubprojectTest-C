project(
  'thinger',
  'c',
  meson_version : '>= 1.3.0',
  version : '0.1',
  default_options : ['warning_level=3'],
)

subproject('gizmo')

dependencies = [
]

executable(
  'thinger',
  'thinger.c',
  dependencies : dependencies,
  install : true,
)
