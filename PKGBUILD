# Generated by debtap
# Maintainer: Zhafron
# Contributor: Zhafron
pkgname=scrin.io
pkgver=1.0.7
pkgrel=1
pkgdesc="Scrin.io - Ethical time tracking"
arch=('i686' 'x86_64')
url="https://scrin.io"
license=('')
groups=('')
depends=('alsa-lib' 'at-spi2-core' 'cairo' 'dbus' 'desktop-file-utils' 'gnome-screenshot' 'expat' 'glib2' 'gtk2' 'gtk3' 'hicolor-icon-theme' 'libcups' 'libdrm' 'libnotify' 'libsecret' 'libx11' 'libxcb' 'libxcomposite' 'libxdamage' 'libxext' 'libxfixes' 'libxrandr' 'libxss' 'libxtst' 'mesa' 'nspr' 'nss' 'pango' 'util-linux-libs' 'xdg-utils')
optdepends=('libappindicator-gtk3')
options=('!strip' '!emptydirs')
install=${pkgname}.install
source_x86_64=("PUT_FULL_URL_FOR_DOWNLOADING_amd64_DEB_PACKAGE_HERE")
sha512sums_x86_64=('803d5e2011d031cd8efac39950de15b7a95ac626c36d4bbb0fbc933a9d6b111aafd2b3b8443de3d1772f2112a85282aab9c72392bcde8f7d1308cd03ddc4d8a1')

package(){

	# Extract package data
	tar -xJ -f data.tar.xz -C "${pkgdir}"

	install -D -m644 "opt/scrin.io/LICENSES.chromium.html" "${pkgdir}/usr/share/licenses/${pkgname}/LICENSE"

}
