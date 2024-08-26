project('sphere-environment-agent', 'c',
        version : '1.0.0',
        default_options : ['warning_level=3', 'c_std=c2x'])

sphere_environment_agent = executable('sphere_environment_agent', 'main.c', install : true)

test('test', sphere_environment_agent)