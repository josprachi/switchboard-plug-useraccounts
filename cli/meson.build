executable(
    'guest-session-toggle',
    'GuestSessionToggle.vala',
    dependencies: [
        dependency('glib-2.0'),
        dependency('gio-2.0'),
        posix_dep
    ],
    install : true,
    install_dir : join_paths(switchboard_dep.get_pkgconfig_variable('plugsdir'), 'system', 'pantheon-useraccounts')
)
