# DorukLauncher 2.4

Modern, şık ve cracked/çevrimdışı hesap destekli Minecraft Mod Başlatıcısı.
**Linux (Ubuntu/Debian) ve Apple macOS (M1/M2/M3/M4 & Intel)** tam uyumlu!

---

## 🍏 Apple macOS (MacBook / iMac / Mac mini) Kurulumu & Çalıştırma

DorukLauncher, macOS üzerinde Apple Silicon (M-Serisi) ve Intel işlemcileri tam olarak destekler.

### Yöntem 1: macOS Uygulaması Olarak (.app)
1. Oluşturulan `DorukLauncher_macOS.zip` dosyasını Mac'inize aktarın ve açın (veya doğrudan `DorukLauncher.app` klasörünü **Applications / Uygulamalar** klasörüne sürükleyin).
2. Çift tıklayarak açabilirsiniz!

### Yöntem 2: Terminal / Script ile Çalıştırma
```bash
./launch_mac.sh
```
*Bu script Mac'inizde eksik olan kütüphaneleri (PyQt6, minecraft-launcher-lib vb.) ve Homebrew / sistem Java sürümlerini otomatik kontrol eder ve başlatır.*

Paketi yeniden derlemek isterseniz:
```bash
./build_mac_app.sh
```

---

## 🐧 Linux (.deb) Paketi Olarak Kurulum

Ubuntu / Debian sistemlerde:

```bash
sudo dpkg -i doruklauncher_2.2.0_all.deb
```

Kurulduktan sonra:
- Uygulama menüsünde **DorukLauncher** olarak logonuzla yer alır.
- Terminalden doğrudan `doruklauncher` komutuyla da başlatılabilir.

Paketi sıfırdan yeniden derlemek isterseniz:
```bash
./build_deb.sh
```

---

## ✨ Özellikler

- **Cracked / Çevrimdışı Hesap:** İstediğin kullanıcı adını yazarak anında oyuna gir (şifre veya Microsoft hesabı gerektirmez).
- **Desteklenen Mod Motorları & Sürümler:**
  - ⚡ **Fabric 1.21.11** (En yeni sürüm ve modlar)
  - ⚡ **Fabric 1.20.1** (En popüler kararlı sürüm)
  - 🔨 **Forge 1.20.1** (Geniş forge mod arşivi)
- **Komple İçerik Yöneticisi:**
  - ⚡ **Modlar (.jar):** Sürükle-bırak, mod aç/kapa (`.disabled`), mod klasörünü açma.
  - 🎨 **Resource Packs / Doku Paketleri (.zip):** Sürükle-bırak, kolay ekleme, doku klasörünü açma.
  - ✨ **Shader Packs (.zip):** Sürükle-bırak, tek tıkla shader ekleme ve shader klasörünü açma.
  - Her profilin modları, dokuları ve shaderları izole edilmiş klasörlerde saklanır.
- **Akıllı Java Tespiti:** Linux ve macOS (Homebrew, `/Library/Java/...`, `/usr/libexec/java_home`) üzerindeki Java 17 ve Java 21 sürümlerini otomatik algılar.
- **RAM Ayarı:** 2 GB - 16 GB arası kolay RAM kaydırıcısı ve gelişmiş JVM parametreleri.
- **Canlı Konsol:** Oyun loglarını ve indirme süreçlerini anlık izleme.
