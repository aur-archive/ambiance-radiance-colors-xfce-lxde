# Maintainer: Spike29 <leguen.yannick@gmail.com>
# Contributor: Dan Serban

pkgname='ambiance-radiance-colors-xfce-lxde'
pkgver='12.04.rev1'
pkgrel=2
pkgdesc="Ambiance & Radiance color themes for Xfce and LXDE"
arch=('any')
license=('GPL2')
url="http://ravefinity.blogspot.com/"
depends=('gtk-engine-murrine' 'gtk-engine-unico')
source=('http://dl.dropbox.com/u/85873590/Ambiance%26Radiance-Colors-XfceLXDE-12-04.tar.gz')
md5sums=('3670700578e07938e7ceaaa04ad5dab9')

package() {
  	mkdir -p "$pkgdir/usr/share/themes/"
	cd "$srcdir/"
	cp -r Ambiance-* "$pkgdir/usr/share/themes"
	cp -r Radiance-* "$pkgdir/usr/share/themes"
	cp -r Classic-* "$pkgdir/usr/share/themes"
}
