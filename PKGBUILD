pkgname=bipp
pkgver=1.0.0
pkgrel=1
pkgdesc='package manager for your music library'
arch=('x86_64')
url='https://github.com/volbot/bipp'
license=('GPL')
depends=('bash>=5.2.021-1' 'deemix>=3.6.6-4')
provides=("${pkgname%-bin}")
conflicts=("${pkgname%-bin}")
source=("${pkgname}-${pkgver}"::"${url}/releases/download/${pkgver}/${pkgname}-${pkgver}-${CARCH}-unknown-linux-musl")
noextract=("${pkgname}-${pkgver}")
sha256sums=('25fe7231b835fbed62be17a847ff04c54da9a9e8d0691ffe492650be023a64fa')

package() {
  mv "${pkgname}-${pkgver}" "${pkgname%-bin}"
  install -Dm0755 -t "${pkgdir}/usr/bin/" "${pkgname%-bin}"
}
