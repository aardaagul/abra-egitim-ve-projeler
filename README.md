# ABRA Eğitim ve Projeler

ABRA yazılım eğitimindeki uygulamaları, akış şemalarını ve ileride hazırlanacak projeleri tek bir düzenli depoda toplamak için hazırlanmıştır.

## Kapsam ve mevcut durum

| Çalışma | Durum |
| --- | --- |
| GitHub teslim klasörleri ve README dosyaları | GitHub’a yüklendi |
| GitHub public repo ve push | Public repo oluşturuldu; dosyalar web arayüzünden yüklendi |
| Algoritma örnekleri | Beş düzenlenebilir Draw.io ve beş PNG hazır; örnek girdilerle kontrol edildi |
| GitHub ve algoritma eğitim videoları | İzlendi |
| Ubuntu kurulumu | Kurulum aşamasında (WSL mevcut) |
| uname -a ekran görüntüsü | Kurulum tamamlandıktan sonra eklenecek |
| Takıma repo bağlantısının iletilmesi ve değerlendirme | Yapıldı |

## Klasör yapısı

```text
abra-egitim-ve-projeler/
├── README.md
├── .gitignore
├── 01-ubuntu-kurulumu/
│   └── README.md
└── 02-algoritma/
    ├── README.md
    └── flowcharts/
        ├── 01-iki-sayinin-toplami.drawio / .png
        ├── 02-tek-cift-kontrolu.drawio / .png
        ├── 03-en-buyuk-sayi.drawio / .png
        ├── 04-birden-nye-toplam.drawio / .png
        └── 05-faktoriyel.drawio / .png
```

[Algoritma çalışmaları](02-algoritma/README.md) · [Ubuntu teslim durumu](01-ubuntu-kurulumu/README.md)

Eğitim kapsamı algoritma, Python/C++, PyQt5, ZeroMQ, gömülü sistemler, temel havacılık, OpenCV ve uçuş simülasyonu çalışmalarını içerir. İleriki aşamaların klasörleri çalışma üretildikçe eklenecektir.

## Belgeyle ilişki ve teslim

EĞİTİM PROGRAMI belgesinin 2. bölümü tek bir public GitHub deposu, görev başına alt klasör ve ana README ister. 3. bölüm akış şemalarını görsel/PDF veya erişilebilir Draw.io bağlantısı olarak kabul eder; Draw.io kaynakları da eklenebilir. Burada PNG ve düzenlenebilir kaynak birlikte hazırlanmıştır.

Bu depoda algoritmik düşünme, koşullar ve döngüler üzerine beş **örnek çalışma** yer alır. Örnekler eğitim belgesinde verilmiş resmî zorunlu sorular değildir.

