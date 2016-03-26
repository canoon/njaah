# Maintainer:  canoon

pkgname=njaah
pkgver=1
pkgrel=1
pkgdesc="An AUR helper based on git submodules"
arch=('any')
url='https://github.com/canoon/njaah'
license=('MIT')
depends=('pyalpm'
         'python-requests'
         'python-termcolor'
         'git')
source=('njaah'
        'README.md')
md5sums=('SKIP'
         'SKIP')

package() {
  mkdir -p "${pkgdir}/usr/bin/"
  cp njaah "${pkgdir}/usr/bin/"
}

# vim:set ts=2 sw=2 et:
