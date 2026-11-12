# YOLO Field Operations

Field inspection demo for detecting cracks, rust, and missing parts with YOLOv8.

---

## Türkçe

Sahada çekilen görsellerde çatlak, pas ve eksik parça tespiti için YOLOv8 tabanlı demo projesi. Depo şu anda ekip geliştirmesi için Python ortamı ve bağımlılıkları sağlar; uygulama arayüzü ve akışı henüz geliştirilmemiştir.

### Gereksinimler

- Python 3.12
- Git

### Kurulum (Windows / PowerShell)

```powershell
py -3.12 -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements-dev.txt
```

VS Code, `.venv` ortamını varsayılan yorumlayıcı olarak kullanır. CUDA/GPU'ya özel PyTorch kurulumu, hedef donanım netleştiğinde belirlenecektir.

### Ekip geliştirme

1. Depoyu klonlayıp yukarıdaki ortam kurulumunu tamamlayın.
2. Değişiklikleri ayrı bir özellik dalında geliştirin.
3. Veri kümelerini, model ağırlıklarını ve yerel ayarları Git'e eklemeyin; `.gitignore` bu dosyaları dışarıda tutar.

**Mevcut durum:** Uygulama kodu, model ağırlıkları ve örnek saha verisi henüz eklenmemiştir.

**Uyarı:** Bu proje eğitim ve demo amaçlıdır; resmî veya sertifikalı bir denetim aracı değildir. Tespit sonuçlarının doğruluğu garanti edilmez. Güvenlik açısından kritik değerlendirmelerde tek başına kullanılmamalıdır. Proje "olduğu gibi" sunulur; kullanım riski kullanıcıya aittir.

---

## English

A YOLOv8 demo project for detecting cracks, rust, and missing parts in images captured in the field. The repository currently provides a Python environment and dependencies for team development; the application interface and workflow have not been implemented yet.

### Requirements

- Python 3.12
- Git

### Setup (Windows / PowerShell)

```powershell
py -3.12 -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements-dev.txt
```

VS Code uses `.venv` as the default interpreter. CUDA/GPU-specific PyTorch installation will be decided once the target hardware is known.

### Team development

1. Clone the repository and complete the environment setup above.
2. Make changes on a separate feature branch.
3. Do not commit datasets, model weights, or local settings; `.gitignore` excludes these files.

**Current status:** Application code, model weights, and sample field data have not been added yet.

**Disclaimer:** This project is for educational and demonstration purposes; it is not an official or certified inspection tool. Detection accuracy is not guaranteed. Do not rely on it alone for safety-critical assessments. The project is provided "as is"; use it at your own risk.
