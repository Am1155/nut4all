# nut4all

Unified discrete-space simulation toolkit for NUT theory  
(نرم‌افزار جامع شبیه‌سازی نظریهٔ فضای گسسته انرژی)

## درباره پروژه

`nut4all` یک بستهٔ نرم‌افزاری منبع‌باز برای شبیه‌سازی دینامیک گرانشی و کیهان‌شناسی در چارچوب نظریهٔ NUT (Network Unified Theory) است. این ابزار شامل حل‌گرهای معادلات emergent، ماژول‌های SU(3) شبکه‌ای، شبیه‌سازی λ–φ، محاسبه G(ρ) و تحلیل منحنی چرخش کهکشان‌ها بدون ماده تاریک است.

## ساختار ماژول‌ها

- `nut.cell` : حل‌گر λ–φ در شبکه گسسته
- `nut.cosmo` : محاسبه G(z)، ε(z)، و طیف CMB با کلاس اصلاح‌شده (CLASS‑NUT)
- `nut.gauge` : پیمانه‌های SU(2), SU(3) با الگوریتم Heat-Bath و Overrelax
- `nut.nbody` : شبیه‌سازی N-body با گرانش emergent محلی
- `nut.analyse` : ترسیم منحنی چرخش، طیف C_ℓ، آمار کیهانی

## نصب

در ترمینال:

```bash
git clone https://github.com/Am1155/nut4all.git
cd nut4all
pip install -r requirements.txt
