# Maintainer: Hewol <hewol@proton.me>
pkgname=cgnome
pkgver=0.1.0
pkgrel=0.1.0
pkgdesc="Custom GNOME for aerOS"
arch=('x86_64')
url="https://github.com/hewol/CGNOME"
license=('GPL')

depends=('gnome-shell')
source=("cgnome.sh")

package() {
    cd "$srcdir"
    install -D -m755 customization_script.sh "$pkgdir/usr/bin/cgnome.sh"
}
