connector = shared_module(
    'dleyna-connector-dbus',
    files('connector-dbus.c'),
    dependencies: [
        dependency('gio-2.0', version: '>= 2.28'),
        dependency('glib-2.0', version: '>= 2.28'),
        dependency('dleyna-core-1.0', version: '>= 0.7.0')
    ],
    install: true,
    install_dir: join_paths(get_option('prefix'), get_option('libdir'), 'dleyna-1.0/connectors')
)

