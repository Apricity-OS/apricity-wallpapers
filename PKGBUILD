#Maintainer: Alex Gajewski <agajews@gmail.com>

_pkgname='Apricity Wallpapers'
pkgname=apricity-wallpapers
pkgver=0.1.3
pkgrel=1
pkgdesc='Wallpapers for Apricity OS'
arch=(any)
license=(GPL)
url="https://github.com/Apricity-OS/apricity-wallpapers"
depends=()
source=("apricity-wallpapers.tar.gz")
sha256sums=('677de85ca08e60b6ec828a0450f716c5fc0257f49ae43427800cb544f080a665')
install=apricity-wallpapers.install

package() {
	mkdir -p "${pkgdir}/usr/share/backgrounds"
	cp -rf "${srcdir}/apricity-wallpapers/backgrounds/apricity" "${pkgdir}/usr/share/backgrounds"
	mkdir -p "${pkgdir}/usr/share/gnome-background-properties"
	cp -f "${srcdir}/apricity-wallpapers/apricity-backgrounds.xml" "${pkgdir}/usr/share/gnome-background-properties"
}
