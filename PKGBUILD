#
# Maintainer: Mahmoud Mohamed (00xWolf) <mmsaeed509@gmail.com> , <https://github.com/mmsaeed509>
#

pkgname=exodia-fonts
pkgver=2.1
pkgrel=2
pkgdesc="Fonts For Exodia OS"
arch=('any')
url="https://github.com/Exodia-OS/exodia-fonts.git"
license=('GPL3')
groups=("exodia-skeleton")

prepare() {

	cp -af ../fonts/. ${srcdir}

}

package() {

	(find * -type f -exec install -Dm 644 "{}" "${pkgdir}/usr/share/fonts/exodia/{}" \;)

}
