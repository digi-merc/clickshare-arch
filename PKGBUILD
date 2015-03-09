# Maintainer: Will R (will digi-merc.org)
# Contributors: 

pkgname=barco-clickshare
pkgver=01.07.00.29
pkgrel=1
pkgdesc="Barco Clickshare wireless presentation system software"
arch=('x86_64')
url="http://www.barco.com/en/Products-Solutions/Presentation-collaboration/ClickShare-wireless-presentation-system/Full-featured-wireless-presentation-system-for-high-profile-meeting-rooms-and-boardrooms.aspx?#!downloads"
license=('proprietary')
depends=('ffmpeg-compat')
optdepends=('')
makedepends=('pacman>=4.2.0')
provides=("clickshare=$pkgver")
options=('!emptydirs' '!strip')
install=$pkgname.install
md5sums_x86_64=('ab26799a646dfee5ad6fceb250fbd6c1')

package() {
  msg2 "Installing..."
  bsdtar -xf data.tar.xz -C "$pkgdir/"

  msg2 "Moving stuff in place..."
  # Icons


  # License
  install -Dm644 eula_text.html "$pkgdir"/usr/share/licenses/google-chrome/eula_text.html

}
