# Contributor: quantax -- contact via Arch Linux forum or AUR
# Maintainer: Ben Reedy <thebenj88 *AT* gmail *DOT* com>

#Big thanks to quantax for making and submitting this.
pkgname=makepkg-lib-unreal
pkgver=0.1
pkgrel=3
pkgdesc="Some shell functions to ease the installation of various Unreal games."
arch=(any)
url="http://aur.archlinux.org/packages.php?ID=26545"
license=('custom') # Is a license applicable to this crap at all?
depends=(xdelta)
source=(unreal.sh)
md5sums=('7ffba31e328d011a59fcdd0ec57b4bcc')

package() {
    cd "${srcdir}"
    install --mode=644 -D -- unreal.sh "${pkgdir}"/usr/lib/makepkg/unreal.sh 
}

