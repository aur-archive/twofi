# This is an example PKGBUILD file. Use this as a start to creating your own,
# and remove these comments. For more information, see 'man PKGBUILD'.
# NOTE: Please fill out the license field for your package! If it is unknown,
# then please put 'unknown'.

# Maintainer: Mauro Andreolini <mauro.andreolini@unimore.it>
pkgname=twofi
pkgver=1.0
pkgrel=2
epoch=
pkgdesc="Twitter Words of Interest"
arch=('any')
url="http://www.digininja.org/projects/twofi.php"
license=('CCPL:cc-by-sa-3.0.txt')
depends=('ruby')
install=
changelog=
source=("http://www.digininja.org/files/twofi_1.0.tar.bz2")
md5sums=('f708460f620fe8159f3ec6cf4f28cc75')

package() {
  install -dm755 ${pkgdir}/usr/share/${pkgname}
  install -Dm644 ${srcdir}/${pkgname}/README ${pkgdir}/usr/share/${pkgname}/README
  install -Dm755 ${srcdir}/${pkgname}/twofi.rb ${pkgdir}/usr/bin/twofi.rb
}

# vim:set ts=2 sw=2 et:
