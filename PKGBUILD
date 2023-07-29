# Maintainer: Jonathan Sanfilippo  <jonalinux dot uk at gmail dot com>
# PKGBUILD per il pacchetto core-icons-theme

pkgname=core-icons-theme
pkgver=1.0
pkgrel=1
pkgdesc="official icons theme Core Linux by Papirus"
arch=('any')
url="https://esempio.com/"

# dipendenze necessarie
depends=('gtk-update-icon-cache')

# comandi di installazione
package() {
    # crea la directory di destinazione
    mkdir -p "${pkgdir}/usr/share/icons/"
    # copia i file nella directory di destinazione
    cp -r Core "${pkgdir}/usr/share/icons/Core"

}
