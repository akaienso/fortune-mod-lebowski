# Maintainer: Rob Moore <abide@thedude.dev>:
pkgname=fortune-mod-lebowski
pkgver=20190314
pkgrel=1
pkgdesc="Fortune cookies: The Big Lebowski quotes (With optional ascii art)."
arch=('any')
license=('GPL')
depends=(fortune-mod)
source=('The Big Lebowski')
url="http://en.wikiquote.org/wiki/The_Big_Lebowski"
md5sums=('a2e304928f2e204a3a66c6fd5e857010')

build() {
  cd $startdir/src

  strfile lebowski lebowski.dat
  strfile lebascii lebascii.dat

  install -D -m644 lebowski $startdir/pkg/usr/share/fortune/lebowski
  install -D -m644 lebowski.dat $startdir/pkg/usr/share/fortune/fr/lebowski.dat
  install -D -m644 lebascii $startdir/pkg/usr/share/fortune/lebascii
  install -D -m644 lebascii.dat $startdir/pkg/usr/share/fortune/fr/lebascii.dat                                                                                   
}
