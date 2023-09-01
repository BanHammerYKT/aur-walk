# Maintainer: BanHammer
pkgname=walk-bin
_reponame=walk
pkgver=1.6.2
pkgrel=1
pkgdesc='Walk — a terminal navigator.'
arch=(x86_64)
url="https://github.com/antonmedv/$_reponame"
license=(MIT)
depends=()
makedepends=(git)
source=("$url/releases/download/v$pkgver/walk_linux_amd64")
sha256sums=('SKIP')

package() {
	install -D -m755 walk_linux_amd64    "$pkgdir/usr/local/bin/walk"
}
