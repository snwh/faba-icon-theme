project('faba-icon-theme',
    version: '4.2',
    meson_version: '>= 0.40',
    license: 'CC-by-SA',
    default_options: ['prefix=/usr']
)

install_subdir('Faba',
    install_dir: join_paths(get_option('prefix'), 'share/icons')
)

meson.add_install_script('meson/post_install.py')
