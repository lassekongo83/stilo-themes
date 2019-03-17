project('Stilo', 'Stajl',
        meson_version: '>= 0.45',
        license : ['GPL3'],
        default_options: ['prefix=/usr'])

sassc = find_program('sassc')

gtk_theme_dir = join_paths(get_option('datadir'), 'themes')

subdir('src')
