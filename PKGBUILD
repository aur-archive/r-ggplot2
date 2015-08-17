# Maintainer: Tobias Neumann <mail at tobias dash neumann dot eu>
# Contributor: Nick B <Shirakawasuna at gmail _dot_com>

pkgname=r-ggplot2
pkgver=0.9.3.1
pkgrel=1
pkgdesc="An implementation of the grammar of graphics in R."
arch=('i686' 'x86_64')
url="http://cran.r-project.org/web/packages/ggplot2/index.html"
license=('GPL-2')
depends=('r' 'r-colorbrewer' 'r-colorspace' 'r-digest' 'r-proto' 'r-reshape2' 'r-gtable>=0.1.1' 'r-memoise' 'r-scales' 'r-plyr')
source=(http://cran.r-project.org/src/contrib/ggplot2_$pkgver.tar.gz)


package() {
    mkdir -p $pkgdir/usr/lib/R/library
    cd $srcdir
    R CMD INSTALL -l $pkgdir/usr/lib/R/library ./ggplot2
}

md5sums=('f01d950c6385750e737ac7eac6260c87')
