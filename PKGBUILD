pkgname=thinkwatt
pkgver=0.2
pkgrel=4
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
md5sums=('b69175d8acd77797218d47fd86513144')
