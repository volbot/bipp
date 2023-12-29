pkgname=bipp
pkgver=1.0.0
pkgrel=1
pkgdesc='package manager for your music library'
arch=('any')
url='https://github.com/volbot/bipp'
license=('GPL')
depends=('bash' 'deemix' 'curl')
makedepends=('git')
source=("git+https://github.com/volbot/bipp.git#tag=v${pkgver}")
sha256sums=('SKIP')

package() {
  cd $pkgname
  install -Dm0755 -t "${pkgdir}/usr/bin/"
}
