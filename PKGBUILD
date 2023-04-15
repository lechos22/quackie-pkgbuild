# Maintainer: lechos22 <mail.lechos22@gmail.com>
pkgname=quackie
pkgver=0.1.0
pkgrel=1
epoch=
pkgdesc="Rotating duck for your terminal"
arch=('any')
url=""
license=('Unlicense')
groups=()
depends=('ncurses')
makedepends=()
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=("https://github.com/lechos22/quackie/archive/refs/heads/main.zip")
sha256sums=('9037dc7c2cd50b536a52045b898bc9ca44bd2197036789c529b32a947578a278')

prepare() {
    # No preparation needed
    :
}

build() {
    # Compile the program
    cd quackie-main
    make
}

check() {
    # No tests provided
    :
}

package() {
	# Install
    cd quackie-main
    DESTDIR="$pkgdir" make install
}

