# Maintainer:  Thomas Dziedzic < gostrc at gmail >
# Contributor: Sergej Pupykin <pupykin.s+arch@gmail.com>
# Contributor: William Rea <sillywilly@gmail.com>

pkgname=pymsn
pkgver=0.3.3
pkgrel=2
pkgdesc='A msn python library, rewrite of the Ivy library.'
arch=('i686' 'x86_64')
url='http://telepathy.freedesktop.org/wiki/Pymsn'
license=('GPL')
depends=('pygobject' 'adns-python' 'pyopenssl' 'pycrypto')
source=("http://telepathy.freedesktop.org/releases/$pkgname/$pkgname-$pkgver.tar.gz")
md5sums=('dbdb6f92569bae784084f0c3a146eb5b')

build() {
  cd $pkgname-$pkgver

  python setup.py install --root="$pkgdir" || return 1
}
