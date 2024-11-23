pkgname=swww-wallpaper-change
pkgver=1.1
pkgrel=1
arch=('any')
pkgdesc='Swaps swww wallpapers'
source=(wc wc-add wc-del)
sha256sums=('83306fdd4fb0cca8f0179810717c6531c50fa8b09defcdaf4c355b7d699fd16b')

pkgver() {
	echo "$pkgver"
}

package() {
	mkdir "$pkgdir/usr/share/swww-wc/wallpapers"
	install -D -t "$pkgdir/usr/bin/swww-wc" "$srcdir/wc" "$srcdir/wc-add" "$srcdir/wc-del"
}
