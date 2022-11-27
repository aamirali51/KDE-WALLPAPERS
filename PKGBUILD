# Maintainer: DarkXero <info@techxero.com>
pkgname=kde-wallpapers
_destname1="/"
pkgver=22.12
pkgrel=1
pkgdesc="KDE Desktop Wallpapers"
arch=('any')
url="https://github.com/aamirali51/"
license=('GPL3')
makedepends=('git')
depends=()
conflicts=()
provides=("${pkgname}")
options=(!strip !emptydirs)
source=(${pkgname}::"git+${url}/${pkgname}")
sha256sums=('SKIP')
package() {
	install -dm755 ${pkgdir}${_destname1}
	cp -r ${srcdir}/${pkgname}${_destname1}/* ${pkgdir}${_destname1}
}
