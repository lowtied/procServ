configure_file(
  input: 'config.h.in',
  output : 'config.h',
  configuration : conf_data
)

procServ_sources = [
  'processFactory.cc',
  'clientFactory.cc',
  'connectionItem.cc',
  'acceptFactory.cc',
  'procServ.cc',
  'forkpty.c',
]

procServ = executable(
  'procServ',
  procServ_sources,
  dependencies: [
    telnet_dep
  ],
  install: true
)
