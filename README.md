<div align="center">

# Vira V2Ray Configs

**Fresh, tested configs · Auto-synced**

[![Channel](https://img.shields.io/badge/Telegram-viraconfigs-26A5E4?logo=telegram&logoColor=white)](https://t.me/viraconfigs)
[![Bot](https://img.shields.io/badge/Bot-vira__boxbot-26A5E4?logo=telegram&logoColor=white)](https://t.me/vira_boxbot)
[![Repo](https://img.shields.io/badge/GitHub-vira--v2ray--configs-181717?logo=github)](https://github.com/PlanAslii/vira-v2ray-configs)

**[English](#-english)** · **[فارسی](#-فارسی)**

</div>

---

# 🇬🇧 English

## What is Vira?

**Vira** aggregates public V2Ray-compatible configurations, checks them, and publishes clean subscription files.

| Link | URL |
|------|-----|
| Channel | https://t.me/viraconfigs |
| Bot | https://t.me/vira_boxbot |
| Repository | https://github.com/PlanAslii/vira-v2ray-configs |

Protocols: **VLESS · VMess · Trojan · Shadowsocks** (+ Telegram MTProto proxies in a separate file).

## How configs are checked

Before a config is stored and synced:

1. **Duplicate filter** — repeated links are skipped
2. **Connectivity test** — TCP and/or **Xray-core** (real outbound test when enabled)
3. Only links that pass are kept for the channel, the bot pool, and this repo

Tests run on servers **outside Iran**. A config may appear online from the test server but still fail on some networks.

## Repository structure

```text
all.txt                 All recent V2Ray configs
countries/XX.txt        By country (NL, DE, IR, …)
protocols/vless.txt
protocols/vmess.txt
protocols/trojan.txt
protocols/ss.txt
Telegramproxy.txt       All Telegram proxies (one file)
```

## Subscription URLs

### Global

```text
https://raw.githubusercontent.com/PlanAslii/vira-v2ray-configs/main/all.txt
```

### By protocol

```text
https://raw.githubusercontent.com/PlanAslii/vira-v2ray-configs/main/protocols/vless.txt
https://raw.githubusercontent.com/PlanAslii/vira-v2ray-configs/main/protocols/vmess.txt
https://raw.githubusercontent.com/PlanAslii/vira-v2ray-configs/main/protocols/trojan.txt
https://raw.githubusercontent.com/PlanAslii/vira-v2ray-configs/main/protocols/ss.txt
```

### By country (examples)

```text
https://raw.githubusercontent.com/PlanAslii/vira-v2ray-configs/main/countries/NL.txt
https://raw.githubusercontent.com/PlanAslii/vira-v2ray-configs/main/countries/DE.txt
https://raw.githubusercontent.com/PlanAslii/vira-v2ray-configs/main/countries/US.txt
https://raw.githubusercontent.com/PlanAslii/vira-v2ray-configs/main/countries/IR.txt
```

### Telegram proxies

```text
https://raw.githubusercontent.com/PlanAslii/vira-v2ray-configs/main/Telegramproxy.txt
```

### CDN mirror (jsDelivr)

```text
https://cdn.jsdelivr.net/gh/PlanAslii/vira-v2ray-configs@main/all.txt
https://cdn.jsdelivr.net/gh/PlanAslii/vira-v2ray-configs@main/Telegramproxy.txt
```

## How to use

1. Install a client: **v2rayNG**, **Hiddify**, **V2RayN**, **Streisand**, …
2. Add a subscription URL from the list above
3. Update → connect

Or use the bot: [@vira_boxbot](https://t.me/vira_boxbot) → choose country / protocol → get a filtered list.

## Updates

Files are refreshed automatically (about every **30 minutes**) from recent working configs.

## Disclaimer

For personal use. Publicly shared configs only. Follow the laws of your country.

---

# 🇮🇷 فارسی

## ویرا چیست؟

**ویرا** کانفیگ‌های عمومی سازگار با V2Ray را جمع می‌کند، بررسی می‌کند و به‌صورت فایل سابسکریپشن منتشر می‌کند.

| مورد | آدرس |
|------|------|
| کانال | https://t.me/viraconfigs |
| ربات | https://t.me/vira_boxbot |
| مخزن | https://github.com/PlanAslii/vira-v2ray-configs |

پروتکل‌ها: **VLESS · VMess · Trojan · Shadowsocks** و فایل جدا برای **پروکسی تلگرام**.

## نحوهٔ بررسی کانفیگ‌ها

قبل از ذخیره و همگام‌سازی:

1. **حذف تکراری** — لینک‌های تکراری رد می‌شوند
2. **تست اتصال** — TCP و در صورت فعال بودن، تست واقعی با **هسته Xray**
3. فقط موارد سالم وارد کانال، ربات و این ریپو می‌شوند

تست روی سرور **خارج از ایران** انجام می‌شود؛ ممکن است کانفیگ از نظر سرور آنلاین باشد ولی در بعضی شبکه‌ها وصل نشود.

## ساختار ریپو

```text
all.txt                 همهٔ کانفیگ‌های V2Ray اخیر
countries/XX.txt        بر اساس کشور
protocols/vless.txt
protocols/vmess.txt
protocols/trojan.txt
protocols/ss.txt
Telegramproxy.txt       همهٔ پروکسی‌های تلگرام در یک فایل
```

## لینک سابسکریپشن

### کلی

```text
https://raw.githubusercontent.com/PlanAslii/vira-v2ray-configs/main/all.txt
```

### بر اساس پروتکل

```text
https://raw.githubusercontent.com/PlanAslii/vira-v2ray-configs/main/protocols/vless.txt
https://raw.githubusercontent.com/PlanAslii/vira-v2ray-configs/main/protocols/vmess.txt
https://raw.githubusercontent.com/PlanAslii/vira-v2ray-configs/main/protocols/trojan.txt
https://raw.githubusercontent.com/PlanAslii/vira-v2ray-configs/main/protocols/ss.txt
```

### بر اساس کشور (نمونه)

```text
https://raw.githubusercontent.com/PlanAslii/vira-v2ray-configs/main/countries/NL.txt
https://raw.githubusercontent.com/PlanAslii/vira-v2ray-configs/main/countries/DE.txt
https://raw.githubusercontent.com/PlanAslii/vira-v2ray-configs/main/countries/US.txt
https://raw.githubusercontent.com/PlanAslii/vira-v2ray-configs/main/countries/IR.txt
```

### پروکسی تلگرام

```text
https://raw.githubusercontent.com/PlanAslii/vira-v2ray-configs/main/Telegramproxy.txt
```

### آینه CDN (jsDelivr)

```text
https://cdn.jsdelivr.net/gh/PlanAslii/vira-v2ray-configs@main/all.txt
https://cdn.jsdelivr.net/gh/PlanAslii/vira-v2ray-configs@main/Telegramproxy.txt
```

## روش استفاده

1. کلاینت نصب کنید: **v2rayNG**، **Hiddify**، **V2RayN**، **Streisand** و …
2. یکی از لینک‌های بالا را به‌عنوان **Subscription** اضافه کنید
3. آپدیت بگیرید و وصل شوید

یا ربات [@vira_boxbot](https://t.me/vira_boxbot) را باز کنید، کشور یا پروتکل را انتخاب کنید و لیست بگیرید.

## به‌روزرسانی

فایل‌ها به‌صورت خودکار (حدود هر **۳۰ دقیقه**) از کانفیگ‌های سالم اخیر به‌روز می‌شوند.
.

---

<div align="center">

[Channel](https://t.me/viraconfigs) · [Bot](https://t.me/vira_boxbot) · [GitHub](https://github.com/PlanAslii/vira-v2ray-configs)

</div>
