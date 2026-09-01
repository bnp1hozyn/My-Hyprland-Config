# My Hyprland Config

Hyprland + Waybar dotfiles.

## Kurulum

```bash
git clone https://github.com/bnp1hozyn/My-Hyprland-Config.git
cp -r My-Hyprland-Config/hypr/. ~/.config/hypr/
cp -r My-Hyprland-Config/waybar/. ~/.config/waybar/
```

## Waybar Görünümü

![waybar](./screenshots/waybar.png)

## ⚠️ Önemli Not

`hypr/hyprland.lua` dosyasındaki monitör ayarları **kendi ekran kurulumuma göre sabitlenmiştir**:
- Laptop ekranı: 1366x768
- İkinci monitör (VGA bağlantılı): 1280x720

Farklı bir monitör/çözünürlük kullanıyorsan, `hyprland.lua` içindeki `monitor=` satırlarını kendi ekranına göre güncellemen gerekir.
