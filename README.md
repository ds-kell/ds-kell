# Free open-source tools by ds-kell · Công cụ miễn phí, mã nguồn mở

Three small, free apps that fix everyday annoyances. No ads, no account, no data sent anywhere.
Ba app nhỏ, miễn phí, giải quyết các phiền toái hằng ngày. Không quảng cáo, không cần tài khoản, không gửi dữ liệu đi đâu.

🌐 Website: **https://ds-kell.github.io** · ☕ [Support / Ủng hộ](#-support--ủng-hộ)

| App | What it does | Platform | Download |
|---|---|---|---|
| 🔔 [HyperNotifyFix](#-hypernotifyfix--fix-delayed-notifications-on-xiaomi-hyperos--miui) | Fix late / missing notifications on Xiaomi, Redmi, POCO (HyperOS, MIUI). No root. | Android | [APK](https://github.com/ds-kell/fix-noti-xiaomi/releases/latest) |
| 🔄 [ConvertApp](#-convertapp--free-offline-file-converter) | Convert images, PDF, Word, Excel, PowerPoint, Markdown, HTML offline, in bulk. | Windows · macOS · Linux | [Installers](https://github.com/ds-kell/convert-multi-file/releases/latest) |
| 🖱️ [Kell Auto Clicker](#️-kell-auto-clicker--auto-clicker--macro-recorder) | Record mouse & keyboard once, replay automatically. | Windows · macOS · Linux | [Downloads](https://github.com/ds-kell/kell-auto-clicker/releases/latest) |

---

## 🔔 HyperNotifyFix — fix delayed notifications on Xiaomi HyperOS / MIUI

**Zalo, Messenger, Gmail, Telegram, WhatsApp notifications arriving late, or only when you open the app?** Xiaomi HyperOS aggressively freezes apps and Google Play Services in the background to save battery. HyperNotifyFix checks what is blocking your notifications and fixes it, **without root**, through [Shizuku](https://shizuku.rikka.app/).

- Doze / battery-optimization whitelist, background-run permission, Xiaomi MILLET & low-latency whitelists, MiPush, FCM (Google push) reconnect.
- Every change is **previewed, backed up and reversible**. Dry Run is on by default.
- Keeps fixes alive after reboot and after HyperOS rewrites them.
- Tested on Xiaomi 15 Ultra (HyperOS 3). Other Xiaomi / Redmi / POCO phones on HyperOS or MIUI (Android 8+) should work; please report results.

**Install**
1. Download `HyperNotifyFix-<version>.apk` from [Releases](https://github.com/ds-kell/fix-noti-xiaomi/releases/latest) and install it (allow "Install unknown apps" if asked).
2. Install **Shizuku** from [Google Play](https://play.google.com/store/apps/details?id=moe.shizuku.privileged.api) or [GitHub](https://github.com/RikkaApps/Shizuku/releases).
3. Turn on Developer options: *Settings → About phone →* tap **OS version** 7 times. Then *Additional settings → Developer options →* enable **Wireless debugging** (Wi-Fi must be on).
4. Open Shizuku → **Start via Wireless debugging** → pair with the code shown in Wireless debugging → **Start**.
5. Open HyperNotifyFix → allow Shizuku → pick the apps whose notifications are late → **Run diagnostics** → review → turn off Dry Run → **Apply**.
6. After a reboot, start Shizuku again only if HyperNotifyFix asks for it.

> Battery use may rise slightly. No app can guarantee instant notifications: the sender's server and your network matter too.

---

## 🔄 ConvertApp — free offline file converter

**Convert many files at once, offline, with no upload to any website.** Drag files into the window, pick the target format, done. On Windows you can also right-click files → **Convert to ▸**.

- **Images:** PNG, JPG, WebP, GIF, BMP, TIFF, ICO, SVG → PNG/JPG/WebP…; resize, quality, auto-rotate from EXIF; merge many images into one PDF or one long picture.
- **Documents:** Markdown ↔ HTML, Markdown/HTML → Word (DOCX) or PDF, Word → Markdown/HTML, HTML → PDF/PNG (full-page screenshot).
- **Office:** Word, Excel, PowerPoint (DOCX, XLSX, PPTX, ODT…) → PDF and between Office formats.
- English and Vietnamese interface.

**Install**

| OS | Download from [Releases](https://github.com/ds-kell/convert-multi-file/releases/latest) | First launch |
|---|---|---|
| Windows 10 / 11 | `ConvertApp_<version>_x64-setup.exe` | If SmartScreen warns: *More info → Run anyway* |
| macOS | `…_aarch64.dmg` (Apple M1/M2/M3/M4) or `…_x64.dmg` (Intel) | Drag to Applications, then right-click → **Open** |
| Linux | `.deb` (Ubuntu/Debian) or `.AppImage` (any distro) | `chmod +x ConvertApp*.AppImage` then run it |

Images, Markdown and HTML work out of the box. For Word/PDF/Office the app shows a 🔒 and the exact command to install the free tool it needs ([Pandoc](https://pandoc.org), [LibreOffice](https://www.libreoffice.org), or Edge/Chrome for HTML → PDF).

---

## 🖱️ Kell Auto Clicker — auto clicker & macro recorder

**Automate repetitive clicking and typing.** Record your mouse clicks, key presses, scrolls and drag-and-drops, then replay them as many times as you want, on any screen size.

- **F9** record · **F7** play · **F8** stop (global hotkeys, work while another app is in front).
- Add steps by hand too: click at a point, press keys, scroll, drag-and-drop, delays, comments.
- Save / load macros, repeat N times or for a set duration, natural random mouse paths.
- Java is bundled: nothing else to install.

**Install**

| OS | Download from [Releases](https://github.com/ds-kell/kell-auto-clicker/releases/latest) | First launch |
|---|---|---|
| Windows | `.msi` installer, or `auto-clicker-windows-portable.zip` (unzip, run `auto-clicker.exe`, no install) | SmartScreen: *More info → Run anyway* |
| macOS | `.dmg` (`arm64` = Apple Silicon, `x64` = Intel) | Right-click → **Open**, then allow it in *System Settings → Privacy & Security → Accessibility* |
| Linux | `.deb`, or `.tar.gz` (run `kell-auto-clicker/bin/kell-auto-clicker`) | Global hotkeys need an X11 session (not Wayland) |

---

## 🇻🇳 Tiếng Việt

**HyperNotifyFix – sửa thông báo bị trễ trên Xiaomi.** Thông báo Zalo, Messenger, Gmail… đến muộn hoặc chỉ hiện khi mở app trên Xiaomi, Redmi, POCO (HyperOS, MIUI)? HyperOS chặn app chạy nền để tiết kiệm pin. App này kiểm tra và gỡ các giới hạn đó, **không cần root**, mọi thay đổi đều sao lưu và hoàn tác được.
Cài đặt: tải file APK ở [Releases](https://github.com/ds-kell/fix-noti-xiaomi/releases/latest) → cài [Shizuku](https://play.google.com/store/apps/details?id=moe.shizuku.privileged.api) → bật Tùy chọn nhà phát triển (bấm 7 lần vào *Phiên bản HĐH* trong *Giới thiệu điện thoại*) → bật **Gỡ lỗi không dây** → mở Shizuku, ghép nối và **Bắt đầu** → mở HyperNotifyFix, chọn app bị trễ thông báo → **Chẩn đoán** → tắt Dry Run → **Áp dụng**.

**ConvertApp – chuyển đổi file miễn phí, không cần mạng.** Đổi ảnh PNG/JPG/WebP/SVG, gộp ảnh thành PDF, Word ↔ PDF, Excel/PowerPoint → PDF, Markdown ↔ HTML, hàng loạt file một lúc, không tải file lên web nào. Trên Windows chỉ cần chuột phải vào file → **Chuyển sang ▸**.
Cài đặt: tải ở [Releases](https://github.com/ds-kell/convert-multi-file/releases/latest): Windows chọn file `-setup.exe`, macOS chọn `.dmg`, Linux chọn `.deb` hoặc `.AppImage`. Windows báo SmartScreen thì bấm *More info → Run anyway*; macOS thì chuột phải vào app → **Open**.

**Kell Auto Clicker – tự động click chuột và bàn phím.** Ghi lại thao tác chuột, phím, cuộn, kéo thả rồi phát lại bao nhiêu lần tùy ý. Phím tắt: **F9** ghi, **F7** chạy, **F8** dừng. Không cần cài Java.
Cài đặt: tải ở [Releases](https://github.com/ds-kell/kell-auto-clicker/releases/latest): Windows chọn `.msi` hoặc bản `.zip` chạy luôn không cần cài; macOS chọn `.dmg` rồi cấp quyền *Trợ năng (Accessibility)*; Linux chọn `.deb` hoặc `.tar.gz`.

---

## ☕ Support / Ủng hộ

If my tools help you, you can buy me a coffee. Nếu thấy có ích, bạn có thể mời mình một ly cà phê. Thank you! Cảm ơn bạn!

[![PayPal](https://img.shields.io/badge/PayPal-Donate-00457C?logo=paypal&logoColor=white)](https://paypal.me/truyennt)

<img src="assets/donate-vietqr.jpg" alt="VietQR VietinBank NGUYEN TUAN TRUYEN" width="220">

VietinBank · NGUYEN TUAN TRUYEN · 106879464361

Found a bug or have an idea? Open an issue in the app's repository. Gặp lỗi hay có ý tưởng? Tạo issue trong repo của app.
