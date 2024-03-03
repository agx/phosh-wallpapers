images = [
  'byzantium-abstract-1920x1080.jpg',
  'byzantium-abstract-3840x2160.jpg',
  'byzantium-abstract-720x1440.jpg',
  'logo-3840x2160.svg',
]

install_data(images, install_dir: imagesdir)

conf = configuration_data()
conf.set('imagesdir', imagesdir)

backgrounds = [
  'byzantium-abstract',
  'logo',
]

foreach background : backgrounds
  # List of sizes
  configure_file(
    input: '@0@.xml.in'.format(background),
    output: '@0@.xml'.format(background),
    configuration: conf,
    install: true,
    install_dir: imagesdir,
  )

  # For g-c-c
  configure_file(
    input: 'phosh-@0@.xml.in'.format(background),
    output: 'phosh-@0@.xml'.format(background),
    configuration: conf,
    install: true,
    install_dir: backgroundpropsdir,
  )
endforeach
