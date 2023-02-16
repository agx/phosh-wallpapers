project('phosh-wallpapers',
  version: '0.25.0',
  meson_version: '>= 0.56.2'
)

i18n = import('i18n')

prefix = get_option('prefix')

datadir = join_paths(prefix, get_option('datadir'))
imagesdir = join_paths(datadir, 'phosh', 'backgrounds')
# So g-c-c can find them
backgroundpropsdir = join_paths(datadir, 'gnome-background-properties')

subdir('wallpapers')
