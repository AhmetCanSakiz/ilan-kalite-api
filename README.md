# ilan-kalite-api

Eğitim amaçlı, statik bir demo API'sidir. Bir Custom Connector alıştırmasında kullanılır.

Tüm veri kurgusaldır. Gerçek bir ilan, satıcı, fiyat, telefon numarası veya internet adresi içermez.

| Yol | Ne döner |
|---|---|
| `/ilanlar/{ilanNo}.json` | Tek bir ilan. Örnek: `ILN-2026-10001` |
| `/kategoriler/{kategoriKodu}.json` | Bir kategorinin zorunlu bilgileri. Kodlar: `EMLAK`, `VASITA`, `IKINCIEL` |

Olmayan bir ilan numarası 404 döner.
