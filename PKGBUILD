# Maintainer: Sam Hewitt <sam@mokaproject.com>
#
# PKGBUILD for Faba Icon Theme
#
# http://github.com/moka-project/faba-icon-theme
#

pkgname=faba-icon-theme-git
pkgdesc="Faba is a sexy and modern icon theme with Tango influences."
arch=('any')
url="https://github.com/moka-project/faba-icon-theme"
license=('GPL3')
depends=()
makedepends=('git')
optdepends=()
provides=('faba-icons-git')
conflicts=('faba-icons-git')
source=('git+https://github.com/moka-project/faba-icon-theme.git')
md5sums=('SKIP')

pkgver() {
  cd $srcdir/$_pkgname
  echo $(git rev-list --count HEAD).$(git rev-parse --short HEAD)
}

package() {

  # create theme dirs
  install -d -m 755 "$pkgdir"/usr/share/icons/Faba

  # install theme
  cd $srcdir/faba-icon-theme/Faba
  cp -r . "$pkgdir"/usr/share/icons/Faba/
}
