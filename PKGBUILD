pkgname=bipp
pkgver=0.0.2
pkgrel=1
pkgdesc='package manager for your music library'
arch=('any')
url='https://github.com/volbot/bipp'
license=('GPL')
depends=('bash' 'deemix' 'curl')
optdepends=('xdg-user-dirs: XDG directory support')
makedepends=('git')
source=("git+https://github.com/volbot/bipp.git#tag=v${pkgver}")
sha256sums=('SKIP')

package() {
  cd $pkgname
  install -Dm0755 -t "${pkgdir}/usr/bin/"
}
