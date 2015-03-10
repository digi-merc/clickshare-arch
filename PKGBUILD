# Maintainer: Will R (will digi-merc.org)
# Contributors: 

pkgname=barco-clickshare
pkgver=01.07.00.29
pkgrel=1
pkgdesc="Barco ClickShare wireless presentation system software"
arch=('x86_64')
url="http://www.barco.com/en/Products-Solutions/Presentation-collaboration/ClickShare-wireless-presentation-system/Full-featured-wireless-presentation-system-for-high-profile-meeting-rooms-and-boardrooms.aspx?#!downloads"
license=('proprietary')
depends=('ffmpeg-compat')
makedepends=('pacman>=4.2.0')
provides=("clickshare=$pkgver")
source=("https://github.com/digi-merc/clickshare-arch/blob/f3432eb79ceeeb0f4dfc6a152af22884a00b856b/clickshare-linux.tar.gz")
sha256sums=('815f8e6fdc18ada70893a9eea8588a422c1904ec49ffd6af637cb6a0f011f14c')

package() {
	tar -xf clickshare-linux.tar.gz -C "$pkgdir/"
}
# vim:set ts=2 sw=2 et:
