# Redmi - Sistem Klavye Monitörü

Eğitim amaçlı C# kullanılarak geliştirilmiş klavye girişleri izleme projesi

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

## ⚠️ Güvenlik ve Etik Uyarısı

**Bu proje sadece eğitim ve akademik amaçlıdır**

- ❌ Bu kodu kötü niyetli amaçlarla kullanmayın
- ❌ İnsanları izinsiz izlemeyin
- ❌ Yetkisiz kullanım çoğu ülkede suçtur
- ✅ Bu proje, izleme yazılımlarının nasıl çalıştığını anlamak ve korunmak için tasarlanmıştır

## 📋 Açıklama

Redmi, C# programlama dili kullanılarak geliştirilmiş eğitim amaçlı bir klavye izleme yazılımıdır. Aşağıdaki konuları anlamak için tasarlanmıştır:
- Tuş kayıt yazılımlarının çalışma prensipleri
- Windows API ile çalışma
- Dosya yönetimi ve depolama
- C#'ta JSON işleme

## 🛠️ Özellikler

- Gerçek zamanlı klavye tuşları izleme
- JSON dosyası ile esnek yapılandırma
- Verileri metin dosyasına kaydetme
- Basit konsol arayüzü

## 📁 Proje Yapısı

```
Redmi/
├── KeyboardTracker.cs
├── keyboard_config.json
├── Redmi.sln
└── README.md
```

## 🔧 Gereksinimler

- .NET Framework 4.7.2 veya üstü
- Visual Studio 2019 veya üstü
- Newtonsoft.Json paketi

## ⚙️ Kurulum

1. Depoyu klonlayın:
```bash
git clone https://github.com/kullaniciadiniz/redmi.git
```

2. Projeyi Visual Studio'da açın

3. Newtonsoft.Json paketini yükleyin:
```bash
Install-Package Newtonsoft.Json
```

4. Projeyi derleyin:
```bash
Build -> Build Solution
```

## 🚀 Kullanım

### Tuş Yapılandırması:
`keyboard_config.json` dosyasını düzenleyerek tuş düzenini ekleyin:

```json
[
  {
    "KeyCode": 65,
    "KeyCharacter": "A"
  },
  {
    "KeyCode": 13,
    "KeyCharacter": "[ENTER]"
  }
]
```

### Programı Çalıştırma:
```bash
cd bin/Debug
SystemMonitor.exe
```

## 📊 Çıktı Örneği

```
Key pressed: M
Key pressed: e
Key pressed: r
Key pressed: h
Key pressed: a
Key pressed: b
Key pressed: a
Key pressed: [ENTER]
```

## 🎯 Eğitim Hedefleri

- Windows API çalışma prensiplerini anlama
- C#'ta dosya işlemleri öğrenme
- Bilgi güvenliği temellerini inceleme
- Hata ayıklama ve analiz becerileri geliştirme

## 🔒 Güvenlik ve Gizlilik

Kodda çeşitli güvenlik katmanları bulunur:
- Klasör oluşturmadan önce varlık kontrolü
- Hata ve istisna işleme
- Kaynakların güvenli kullanımı

## 🤝 Katkıda Bulunma

Aşağıdaki alanlara odaklanan katkıları memnuniyetle karşılıyoruz:
- Güvenlik iyileştirmeleri
- Eğitim özellikleri ekleme
- Dokümantasyon iyileştirmeleri
- Hata düzeltmeleri

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır - detaylar için [LICENSE](LICENSE) dosyasına bakın.

## 👥 Geliştiriciler

- [Adınız](https://github.com/kullaniciadiniz)

## 📞 Destek

Eğitimsel veya teknik sorularınız varsa, bu depoda bir issue açabilirsiniz.

---

**Unutmayın: Bilgi güçtür, onu bilgece ve sorumlulukla kullanın** 🛡️

```
