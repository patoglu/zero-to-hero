<!-- @author ypatoglu -->

# Neural Networks: Zero to Hero — Türkçe Notlar

Andrej Karpathy'nin [Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html)
serisini izlerken tuttuğum notlar. Her video için ayrı bir Jupyter notebook var.

**Site:** https://patoglu.github.io/zero-to-hero/

## Geliştirme

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

mkdocs serve      # http://127.0.0.1:8000
mkdocs gh-deploy  # GitHub Pages'e yayınla
```

## Yapı

```
docs/
├── index.md
└── notebooks/
    ├── 01-micrograd.ipynb
    ├── 02-makemore.ipynb
    └── ...
```

## Haklar

Seri ve orijinal kod **Andrej Karpathy**'ye aittir (MIT). Türkçe notlar
**Yusuf Patoğlu** tarafından yazılmıştır (CC BY-NC-ND 4.0). Ayrıntı için
[LICENSE](LICENSE) dosyasına bakınız.

Bu depo resmî bir kaynak değildir. Notlar hata içerebilir; çelişki durumunda
orijinal videoyu esas alın.
