project('myproject', 'cpp',
        default_options: ['cpp_std=c++2a',
                          'default_library=static'])

sfml_dep = dependency('sfml-all') # Only system version supported for now.
imgui_sfml_dep = dependency('imgui-sfml',
                            fallback: ['imgui-sfml'])
spdlog_dep = dependency('spdlog', fallback: ['spdlog', 'spdlog_headeronly_dep'])
docopt_dep = dependency('docopt', fallback: ['docopt'])
nlohmann_json_dep = dependency('nlohmann_json', fallback: ['nlohmann_json', 'nlohmann_json_dep'])
fmt_dep = dependency('fmt', fallback: ['fmt', 'fmt_dep'])

subdir('src')
