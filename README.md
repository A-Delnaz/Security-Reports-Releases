# Security Reports — update packages

Update files of **Security Reports** (`Security-Reports-<version>.adup`), one release per version.

- The files are **encrypted and signed**: they can only be opened by Security Reports itself,
  and a changed or fake file is never installed.
- `index.json` in every release lists the version (used by the "web address" update source).
- Installed servers read this repository directly (source "GitHub"), or a shared folder that
  the update mirror fills (see github.com/A-Delnaz/dev-tools, folder `mirror`).

---

# Security Reports — فایل‌های به‌روزرسانی

فایل‌های به‌روزرسانی سامانه‌ی **Security Reports**، یک انتشار برای هر نسخه.
فایل‌ها رمزنگاری‌شده و امضاشده هستند: فقط خود سامانه بازشان می‌کند و فایل تغییرکرده یا جعلی نصب نمی‌شود.
