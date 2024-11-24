pkgname=swww-wallpaper-change
pkgver=1.2
pkgrel=1
arch=('any')
pkgdesc='Swaps swww wallpapers'
source=(wc-swp wc-add wc-del)
sha256sums=('5b55a5b19fa82246db2d7d512b2d5c371292ec023b469cba32f0367daf534abd'
            '7fbd7c0184df249dcf1abfbfb80cd8d9fab153ec0f1bba7cf40ea8a931c41a92'
            'a12b579097e44325c03da6bf70874e2c018e032d78e03eca655523f4584069f0')
pkgver() {
	echo "$pkgver"
}

package() {
	mkdir -p "$pkgdir/usr/share/swww-wc/wallpapers"
	install -D -t "$pkgdir/usr/bin" "$srcdir/wc-swp" "$srcdir/wc-add" "$srcdir/wc-del"
}
