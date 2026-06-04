# Giderio — Tanıtım sitesi

GitHub Pages için statik landing site.

## Yayınlama

1. Bu klasörü bir GitHub repo’suna push edin (ör. `giderio` veya `giderio-website`).
2. **Settings → Pages → Build and deployment → Source:** Deploy from a branch.
3. Branch: `main`, folder: `/` (root).
4. Site adresi: `https://<kullanıcı-adı>.github.io/<repo-adı>/`

`index.html` kökte olduğu için proje sayfası olarak çalışır.

## Sayfalar

| Dosya | Açıklama |
|-------|----------|
| `index.html` | Ana tanıtım (one-page) |
| `download.html` | App Store / Google Play yönlendirme |
| `contact.html` | İletişim |
| `privacy.html` | Gizlilik politikası |
| `account-deletion.html` | Hesap / veri silme (Play Console URL) |

## Mağaza linkleri

`download.html` içindeki `href` değerlerini yayın sonrası güncelleyin.

## Yerel önizleme

```bash
cd /Users/talhacosar29/Web_Projects/giderio
python3 -m http.server 8080
```

Tarayıcı: http://localhost:8080
