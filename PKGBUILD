pkgname=thinkwatt
pkgver=0.3
pkgrel=0
pkgdesc="record power consumption, calculate the average and create a gnuplot graphic"
arch=('any')
url="https://github.com/mikar/thinkwatt"
license=('GPL')
depends=('gawk' 'sed')
optdepends=('gnuplot' 'tp_smapi')
source=(https://github.com/mikar/thinkwatt/raw/master/thinkwatt)

build() {
  install -d	${pkgdir}/usr/bin
  install -m755 ${srcdir}/${pkgname} ${pkgdir}/usr/bin/
  ln -s /usr/bin/${pkgname} ${pkgdir}/usr/bin/twat
}
md5sums=('fff70bbe3ed5be8adc8564ed269a2f9f')
