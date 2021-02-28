project('FractalSoundExplorer', 'cpp',
  version : '0.1',
  default_options : ['warning_level=3', 'cpp_std=c++14'])

sfml = dependency('sfml-all')
opengl = dependency('opengl')

executable('FractalSoundExplorer',
           'Main.cpp',
           dependencies: [sfml, opengl])
