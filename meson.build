project('phosh-wallpapers',
  version: '0.37.0',
  meson_version: '>= 0.56.2'
)

i18n = import('i18n')

prefix = get_option('prefix')

datadir = join_paths(prefix, get_option('datadir'))
imagesdir = join_paths(datadir, 'phosh', 'backgrounds')
sounddir = datadir / 'sounds' / 'phosh'
themedir = datadir / 'plymouth' / 'themes' / 'phosh'
# So g-c-c can find them
backgroundpropsdir = join_paths(datadir, 'gnome-background-properties')

subdir('wallpapers')
subdir('plymouth')
subdir('sounds')
