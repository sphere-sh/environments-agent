project('sphere-environment-agent', 'c',
        version : '1.0.0',
        default_options : ['warning_level=3', 'c_std=c2x'])


sphere_environment_agent_compiler = executable(
        'compiler',
        'compiler/compiler.c',
        'compiler/compiler.h',
        'compiler/lexer.c',
        'compiler/lexer.h',
        'compiler/grammar.c',
        'compiler/grammar.h',
        'compiler/parser.c',
        'compiler/parser.h',
        'compiler/ast.c',
        'compiler/ast.h',
        'compiler/codegen.c',
        'compiler/codegen.h',
        install : true
)

sphere_environment_agent_linker = executable(
        'linker',
        'linker/linker.c',
        'linker/linker.h',
        install : true
)

