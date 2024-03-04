theme = files(
  # The script
  'phosh.script',
  # The used images
 'box.png',
 'bullet.png',
 'entry.png',
 'lock.png',
 'logo.png',
 'progress_bar.png',
 'progress_box.png',
 'spinner-0.png',
 'spinner-1.png',
 'spinner-10.png',
 'spinner-11.png',
 'spinner-12.png',
 'spinner-13.png',
 'spinner-14.png',
 'spinner-15.png',
 'spinner-16.png',
 'spinner-17.png',
 'spinner-18.png',
 'spinner-19.png',
 'spinner-2.png',
 'spinner-20.png',
 'spinner-21.png',
 'spinner-22.png',
 'spinner-23.png',
 'spinner-24.png',
 'spinner-25.png',
 'spinner-26.png',
 'spinner-27.png',
 'spinner-28.png',
 'spinner-29.png',
 'spinner-3.png',
 'spinner-4.png',
 'spinner-5.png',
 'spinner-6.png',
 'spinner-7.png',
 'spinner-8.png',
 'spinner-9.png',
)

install_data(theme, install_dir: themedir)

conf = configuration_data()
conf.set('themedir', themedir)

configure_file(
  input: 'phosh.plymouth.in',
  output: 'phosh.plymouth',
  configuration: conf,
  install: true,
  install_dir: themedir,
)
