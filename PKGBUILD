pkgname=swww-wallpaper-change
pkgver=1.1
pkgrel=1
arch=('any')
pkgdesc='Swaps swww wallpapers'
source=(wc-swp wc-add wc-del)
sha256sums=('5b55a5b19fa82246db2d7d512b2d5c371292ec023b469cba32f0367daf534abd'
            '7fbd7c0184df249dcf1abfbfb80cd8d9fab153ec0f1bba7cf40ea8a931c41a92'
            'f0230abf57056899aaa6333a6fe2f733ea2f1603ee048c446307eea0eff51469')

 pkgver() {
	echo "$pkgver"
}

package() {
	mkdir -p "$pkgdir/usr/share/swww-wc/wallpapers"
	install -D -t "$pkgdir/usr/bin" "$srcdir/wc-swp" "$srcdir/wc-add" "$srcdir/wc-del"
}
