
pkgname=win11-icons-git
_pkgname=win11-icons
_destname1="/usr/share/icons/"
pkgver=23.10
pkgrel=01
pkgdesc="win11-icons"
arch=('any')
url="https://github.com/amanre/win11-icons"
license=('GPL3')
makedepends=('git')
depends=()
provides=("${pkgname}")
options=(!strip !emptydirs)
source=(${_pkgname}::git+https://github.com/amanre/win11-icons.git)
sha256sums=('SKIP')
package() {

	install -dm755 ${pkgdir}${_destname1}
	cp -r  ${srcdir}/${_pkgname}${_destname1}* ${pkgdir}${_destname1}
}
