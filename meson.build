project('TestDubDependency', 'd')

ddbc_dep = dependency('ddbc', method: 'dub')

src = [
    'main.d'
]

executable('main', src, dependencies: [ddbc_dep])