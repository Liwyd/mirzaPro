<div align="center">

# mirzaPro

**A powerful Telegram bot panel for VPN service management**

یک پنل ربات تلگرام قدرتمند برای مدیریت خدمات VPN

[![License](https://img.shields.io/badge/license-AGPL--3.0-blue.svg)](LICENSE)
[![PHP](https://img.shields.io/badge/php-8.3%2F8.4-777BB4.svg)](https://php.net)

---

### Star this repo / لطفاً ستاره بزنید

[![Star](https://img.shields.io/github/stars/Liwyd/mirzaPro?style=social)](https://github.com/Liwyd/mirzaPro/stargazers)

</div>

---

## Features / قابلیت‌ها

| Feature | English | فارسی |
|---------|---------|-------|
| Multi-Panel Support | Marzban, x-ui, Hiddify, Marzneshin | پشتیبانی از پنل‌های مختلف |
| Payment Gateways | Online & Card-to-Card | درگاه پرداخت آنلاین و کارت به کارت |
| User Management | Full admin panel | مدیریت کامل کاربران |
| Subscription System | Buy, Renew, Extend | سیستم اشتراک، تمدید و خرید |
| Backup | Automated database backup | پشتیبانی خودکار دیتابیس |
| Affiliate System | Referral & commission | سیستم زیرمجموعه‌گیری |
| Test Accounts | Free trial configs | اکانت تست رایگان |
| SSL Support | Auto Let's Encrypt | پشتیبانی خودکار SSL |

---

## Requirements / پیش‌نیازها

| Component | Requirement | وضعیت |
|-----------|------------|-------|
| PHP | 8.3 / 8.4 | **Required / اجباری** |
| Cron Job | Enabled | **Required / اجباری** |
| Web Server | Apache / OpenLiteSpeed | Required |

---

## Installation / نصب

### Option 1: Server Script (Recommended) / اسکریپت سرور (پیشنهادی)

Run this command on your server / این دستور را روی سرور خود اجرا کنید:

```bash
bash -c "$(curl -L https://raw.githubusercontent.com/Liwyd/mirzaPro/main/install.sh)"
```

Then select option `1` for fresh install or `2` for update / سپس گزینه `1` برای نصب یا `2` برای آپدیت را انتخاب کنید

### Option 2: Host Upload (cPanel / aaPanel) / آپلود در هاست

1. Download the latest release / آخرین نسخه را دانلود کنید:
   ```
   https://github.com/Liwyd/mirzaPro/releases
   ```

2. Upload ZIP to your host and extract / فایل ZIP را در هاست آپلود و استخراج کنید

3. Open installer in browser / نصب‌کننده را در مرورگر باز کنید:
   ```
   https://your-domain.com/path/installer
   ```

4. Follow the installation steps / مراحل نصب را دنبال کنید

---

## Migration / مهاجرت

### From Free Version to Pro / از نسخه رایگان به پرو

1. Save your `config.php` / فایل `config.php` را ذخیره کنید
2. Delete old source files / فایل‌های قبلی را حذف کنید
3. Upload new version / نسخه جدید را آپلود کنید
4. Open installer and select migration / نصب‌کننده را باز و گزینه مهاجرت را انتخاب کنید

### Server Update / آپدیت سرور

```bash
bash -c "$(curl -L https://raw.githubusercontent.com/Liwyd/mirzaPro/main/install.sh)"
```

Select option `2` to update / گزینه `2` را برای آپدیت انتخاب کنید

---

## Update Guide / راهنمای آپدیت

1. Delete old source (keep `config.php`) / سورس قبلی را حذف کنید (فایل `config.php` را نگه دارید)
2. Upload new version / نسخه جدید را آپلود کنید
3. Delete `installer/` folder after upload / بعد از آپلود پوشه `installer/` را حذف کنید
4. Replace `config.php` content with saved version / محتوای `config.php` را جایگزین کنید
5. Visit `https://your-domain.com/path/index.php` if bot doesn't work / اگر ربات کار نکرد آدرس را در مرورگر باز کنید

---

## aaPanel Setup / تنظیم aaPanel

1. Web server must run on aaPanel with OpenLiteSpeed 1.8.4 / وب‌سرور باید روی aaPanel با OpenLiteSpeed 1.8.4 باشد
2. Follow the host installation guide / راهنمای نصب هاست را دنبال کنید

---

## Support / پشتیبانی

For issues and questions / برای مشکلات و سوالات:

- Open an Issue on GitHub / Issue بسازید در گیتهاب

---

## License / مجوز

This project is licensed under AGPL-3.0 / این پروژه تحت مجوز AGPL-3.0 است

---

<div align="center">

**Made with heart / ساخته شده با عشق**

</div>

---

## Disclaimer

> **This repository is a backup mirror.** The original code is developed by [Mmd-Amir](https://github.com/Mmd-Amir/mirza_pro). This clone is maintained solely to preserve a safe copy in case the original author decides to remove or delete it. All credit for the code goes to the original developer.

## سلب مسئولیت

> **این ریپازیتوری یک نسخه پشتیبان (آینه) است.** کد اصلی توسط [Mmd-Amir](https://github.com/Mmd-Amir/mirza_pro) توسعه داده شده است. این کلون صرفاً برای حفظ یک نسخه امن نگه‌داری می‌شود، در صورتی که ناشر اصلی تصمیم به حذف یا پاک‌سازی ریپازیتوری خود بگیرد. تمامی حقوق کد متعلق به توسعه‌دهنده اصلی است.
