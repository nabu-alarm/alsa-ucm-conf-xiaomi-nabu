pkgname=alsa-ucm-conf-xiaomi-nabu
pkgver=1.0
pkgrel=1
pkgdesc='ALSA ucm2 settings for Xiaomi Mi Pad 5'
url='https://github.com/map220v/ubuntu-xiaomi-nabu/tree/master/alsa-xiaomi-nabu'
arch=(aarch64)
license=("Unknown")
makedepends=(
)
options=(
  !debug
  !strip
)
source=(
  'asla-ucm-conf-xiaomi-nabu.tgz'
)
sha512sums=(
  'dbdd96699332185c6bcbd492ec7e907820edcd10e748feca2009f2776b70855b'
)
depends=(
  'alsa-ucm-conf'
)

package() {
  mkdir -p "$pkgdir"

  cp -r src/* "$pkgdir/"
}

# vim:set ts=8 sts=2 sw=2 et:
