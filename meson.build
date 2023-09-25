project(
  'procServ',
  ['cpp', 'c'],
  version: '2.9.0',
)

conf_data = configuration_data()
conf_data.set('PROCSERV_VERSION_STRING', meson.project_version())

telnet_dep = dependency('libtelnet')

subdir('procServ')
