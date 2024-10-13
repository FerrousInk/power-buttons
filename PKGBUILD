pkgname=power-buttons
pkgver=1.0.0
pkgrel=1
pkgdesc="Adds the power buttons (poweroff, reboot, suspend) to the applications folder"
arch=("x86_64" "aarch64" "armv7h")
url="https://ferrousink.github.io"
license=('MIT')
depends=('systemd')
source=("https://ferrousink.github.io/power-buttons/power-buttons.tar.xz")
sha256sums=('SKIP')

package() {
    sudo install -Dm644 "$srcdir/poweroff.desktop" "$pkgdir/usr/share/applications/poweroff.desktop"
    sudo install -Dm644 "$srcdir/reboot.desktop" "$pkgdir/usr/share/applications/reboot.desktop"
    sudo install -Dm644 "$srcdir/suspend.desktop" "$pkgdir/usr/share/applications/suspend.desktop"
}
