# Maintainer: Ng Oon-Ee <ngoonee.talk@gmail.com>
# Contributor: M Rawash <mrawash@gmail.com>
pkgname=genesis-sync
pkgver=0.7.1
pkgrel=2
pkgdesc="A graphical frontend for SyncEvolution written in PyGTK."
arch=('any')
url="https://launchpad.net/genesis-sync"
license=('GPL')
depends=("syncevolution>=1.0" 'hicolor-icon-theme' 'dbus-python' 'python2-notify' 'python2-wnck')
makedepends=('python-distutils-extra')
source=(http://code.launchpad.net/$pkgname/0.7/$pkgver/+download/${pkgname}_$pkgver.tar.gz)
md5sums=('77df803f1f56b3c56ac6a6e8f8f79cb1')

build() {
  cd "${srcdir}/${pkgname}-gtk3"
  python2 setup.py install --root=$pkgdir
}
