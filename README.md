# Phosh Wallpapers

Phosh wallpapers and other artwork

## License

See [copyright](./debian/copyright) for copyright and author information.

## Getting the source

```sh
git clone https://gitlab.gnome.org/guidog/phosh-wallpapers
cd phosh-wallpapers
```

The [main][] branch has the current development version.

## Installing

This project use the meson (and thereby Ninja) build system.  The quickest way
to get going is to do the following:

```sh
meson setup _build
meson compile -C _build
meson install -C _build
```

which will install the files to `/usr/local` in their respective folders.

[main]: https://gitlab.gnome.org/guidog/phosh-wallpapers/-/tree/main
