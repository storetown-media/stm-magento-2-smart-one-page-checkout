<div align="center">

# ⚡ STM Smart One Page Checkout für Magento 2

### Schneller Checkout · Hyvä + Luma kompatibel · Mollie · Adyen · Klarna · PayPal & mehr

[![Commercial](https://img.shields.io/badge/License-Commercial%20Closed--Source-red?style=flat-square)](#license)
[![Magento](https://img.shields.io/badge/Magento-2.4.x-EE672F?style=flat-square&logo=magento)](#kompatibilit%C3%A4t)
[![PHP](https://img.shields.io/badge/PHP-8.1%E2%80%938.4-777BB4?style=flat-square&logo=php)](#kompatibilit%C3%A4t)
[![Hyvä](https://img.shields.io/badge/Hyv%C3%A4-Native-FF6B35?style=flat-square)](https://www.hyva.io/)
[![Reviews](https://img.shields.io/badge/Reviews-4.83%E2%98%85%20%2F%206-yellow?style=flat-square)](https://www.storetown-media.de/stm-smart-one-page-checkout/)

[🛒 **Kaufen ab 389 €**](https://www.storetown-media.de/stm-smart-one-page-checkout/) · [🎬 **Demo-Video**](https://www.youtube.com/watch?v=BTBDeQMi8kk) · [🖥️ **Live-Demo**](https://magento2-shop.de/demo-stm-smart-checkout-magento) · [📚 **Hub**](https://www.storetown-media.de/produkt-kategorie/downloads/magento-extensions/)

</div>

> ⚠️ **Commercial Closed-Source Extension.** Dieses Repository enthält Dokumentation und Pre-Sales-Informationen. Der Modul-Quellcode wird ausschließlich nach Kauf über die [Produktseite](https://www.storetown-media.de/stm-smart-one-page-checkout/) oder den Adobe Commerce Marketplace ausgeliefert.

---

## Das Problem

> „Bis zu **70 % aller Warenkörbe** werden vor dem Kaufabschluss verlassen — oft wegen eines zu langen oder unübersichtlichen Checkouts."
>
> „Über **60 % aller Online-Bestellungen** werden heute mobil aufgegeben."

Der Standard-Checkout von Magento 2 verteilt den Bestellprozess auf mehrere Seiten. Adresse, Versand, Zahlung, Übersicht — jeder Schritt ein potenzieller Drop-Off-Punkt. Auf Mobilgeräten verschärft sich das Problem dramatisch.

## Die Lösung

**STM Smart One Page Checkout** bringt Adresse, Versand, Zahlung und Bestellübersicht auf **eine einzige Seite** — weniger Klicks, mehr Übersicht, weniger Abbrüche. Vier umschaltbare Layout-Varianten, native Hyvä-Optimierung und 8 Payment-Provider out-of-the-box.

🎬 **Demo-Video ansehen:**

[![Demo-Video Smart Checkout](https://img.youtube.com/vi/BTBDeQMi8kk/maxresdefault.jpg)](https://www.youtube.com/watch?v=BTBDeQMi8kk)

## Features

- ⚡ **One Page Checkout** — Kompletter Bestellprozess auf einer Seite, kein Seitenwechsel
- 🎨 **4 Layout-Varianten** — Two Column · Reverse · One Column · Ultra Compact (per Backend umschaltbar)
- 💳 **8 Payment-Provider** — Mollie · Stripe · PayPal · Klarna · Adyen · PayOne · Unzer · Amazon Pay
- 📱 **Mobile-First** — Touch-optimiert, Sticky-Bestellleiste, kompakte Darstellung
- 🌍 **11 Sprachen** — DE · AT · CH · EN · FR · ES · IT · NL · PL · SE · US
- 📊 **Live-Bestellübersicht** — Warenkorb, Versandkosten, Gesamtpreis immer sichtbar
- 🔧 **Composer-Installation** — alle Einstellungen im Magento-Backend, keine Code-Änderungen

## Zielgruppe

- Shopbetreiber mit zu vielen Checkout-Abbrüchen
- Magento-Agenturen und Entwickler
- Internationale Shops mit mehreren Sprachen
- Shops mit PayPal · Stripe · Mollie oder Klarna
- Mobile-Commerce mit hohem Smartphone-Anteil
- Hyvä- oder Luma-basierte Magento-Shops

## Use-Cases

**Shops mit hoher Checkout-Abbruchrate:** Wenn Analytics zeigen, dass mehr als 60 % der Warenkörbe vor der Bestellung verlassen werden, liegt die Ursache fast immer im Checkout-Flow.

**B2C mit hohem Mobile-Anteil:** Wenn über die Hälfte der Bestellungen mobil eingeht, ist ein Mobile-First-Checkout kein Luxus mehr.

**Internationale Multi-Store-Setups:** Bei Magento Store Views in mehreren Ländern werden 11 vorinstallierte Sprachpakete zum Effizienzvorteil.

## Pricing

| Edition | Für | Preis (inkl. 19 % MwSt.) |
|---|---|---|
| **Community** | Magento Open Source | **389,00 €** |
| **Enterprise** | Adobe Commerce | **649,00 €** |
| **Magento Cloud** | Adobe Commerce Cloud | **729,00 €** |

Alle Editionen: **One-Time Purchase** · 12 Monate Produktaktualisierungen · Pro-Support · **30 Tage Geld-zurück-Garantie**.

→ [**Jetzt kaufen**](https://www.storetown-media.de/stm-smart-one-page-checkout/)

## Kompatibilität

| Anforderung | Details |
|---|---|
| **Magento** | 2.4.x (Open Source + Adobe Commerce + Cloud) |
| **PHP** | 8.1 · 8.2 · 8.3 · 8.4 |
| **Themes** | Hyvä (nativ) · Luma · Porto · Ultimo |
| **Installation** | Composer (empfohlen) oder ZIP |

## Installation

> Composer-Installation funktioniert nach Kauf über den ausgelieferten Auth-Token / das ZIP-Paket. Eine öffentliche Packagist-Distribution ist für Q3/2026 geplant.

```bash
# Nach Kauf:
composer require storetown/module-smart-checkout
bin/magento module:enable Storetown_SmartCheckout
bin/magento setup:upgrade
bin/magento setup:di:compile
bin/magento setup:static-content:deploy
bin/magento cache:flush
```

Alle Einstellungen anschließend unter **Stores → Configuration → STM → Smart Checkout**.

## Live ausprobieren

| | |
|---|---|
| **Frontend-Demo** | [magento2-shop.de/demo-stm-smart-checkout-magento](https://magento2-shop.de/demo-stm-smart-checkout-magento) |
| **Backend-Demo** | [Auto-Login](https://magento2-shop.de/demorole/autologin?token=demo2024stm) |
| **Demo-Video (1:25)** | [YouTube](https://www.youtube.com/watch?v=BTBDeQMi8kk) |

## Support & Pre-Sales

- **Pre-Sales-Fragen:** Issue im [Issues-Tab](../../issues) eröffnen (Template „Pre-Sales Question")
- **Kunden-Support nach Kauf:** Über das Kunden-Konto auf storetown-media.de
- **Installation-Service:** Optional buchbar für 49 € (auf der Produktseite hinzufügen)
- **Email:** info@storetown-media.de

> Bitte **keine Bug-Reports oder Support-Anfragen** in GitHub-Issues — die werden hier nicht bearbeitet. Issues sind ausschließlich für Pre-Sales-Klärungen vor dem Kauf.

## Über Storetown-Media

Seit **2014** Magento-Spezialist im DACH-Raum. 12+ Jahre Praxis in Hyvä, Luma und Adobe Commerce. Mehr unter [storetown-media.de](https://www.storetown-media.de/) oder im [Org-Profil](https://github.com/storetown-media).

## License

**Proprietary / Commercial Closed-Source.** Siehe [LICENSE](LICENSE) sowie die [AGB von Storetown-Media](https://www.storetown-media.de/agb/).

Dieses Repository (Dokumentation, README, Issue-Templates) steht unter All-Rights-Reserved. Der ausgelieferte Magento-Modulcode wird durch die kommerzielle Lizenz im Kaufvertrag geregelt.
