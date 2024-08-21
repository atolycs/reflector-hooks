# This is an example PKGBUILD file. Use this as a start to creating your own,
# and remove these comments. For more information, see 'man PKGBUILD'.
# NOTE: Please fill out the license field for your package! If it is unknown,
# then please put 'unknown'.

# Maintainer: Your Name <youremail@domain.com>
pkgname=reflector-hook
pkgver=1.0.0
pkgrel=1
epoch=
pkgdesc="Update Pacman mirrorlist hook"
arch=("any")
url="https://github.com/atolycs/reflector-hook"
license=('MIT')
groups=()
depends=("reflector")
options=()
source=("99-update-mirrorlist.hook")
sha256sums=('5f8d06995aa28bada32e411dae0ca4b868e6768c21f5432c97346ff39142fad5')
validpgpkeys=()

package() {
  install -Dm644 '99-update-mirrorlist.hook' "${pkgdir}/usr/share/libalpm/hooks/99-update-mirrorlist.hook"
}
