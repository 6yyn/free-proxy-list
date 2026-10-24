# 🚀 Free Proxy List - 6YYN

[![Stars](https://img.shields.io/github/stars/6yyn/free-proxy-list?style=social)](https://github.com/6yyn/free-proxy-list/stargazers)
[![Forks](https://img.shields.io/github/forks/6yyn/free-proxy-list?style=social)](https://github.com/6yyn/free-proxy-list/network/members)
[![Last Commit](https://img.shields.io/github/last-commit/6yyn/free-proxy-list)](https://github.com/6yyn/free-proxy-list/commits/main)
[![Update](https://img.shields.io/badge/Updated-every%203--5%20min-brightgreen)](https://github.com/6yyn/free-proxy-list)

Auto-updated free **HTTP / HTTPS** proxy list.  
Tested against **Google** and **Instagram**. Updated every **3–5 minutes**.

---

## 📥 Download (Raw)

| File | Raw Link | Description |
|------|----------|-------------|
| `proxies.txt` | [Download](https://raw.githubusercontent.com/6yyn/free-proxy-list/main/proxies.txt) | All proxies combined |
| `http.txt` | [Download](https://raw.githubusercontent.com/6yyn/free-proxy-list/main/http.txt) | HTTP proxies |
| `https.txt` | [Download](https://raw.githubusercontent.com/6yyn/free-proxy-list/main/https.txt) | HTTPS proxies |
| `google_proxies.txt` | [Download](https://raw.githubusercontent.com/6yyn/free-proxy-list/main/google_proxies.txt) | Google verified |
| `instagram_proxies.txt` | [Download](https://raw.githubusercontent.com/6yyn/free-proxy-list/main/instagram_proxies.txt) | Instagram verified |

---

## 📊 Live Stats

- 🔹 **Google Working:** 830
- 🔹 **Instagram Working:** 721
- 🔹 **Last Update:** 2026-10-23 18:30:36
- 🔹 **Update Frequency:** Every 3–5 minutes

---

## 🔧 Usage

### Python
```python
import requests

url = "https://raw.githubusercontent.com/6yyn/free-proxy-list/main/proxies.txt"
proxies_list = requests.get(url).text.strip().split("\n")

proxy = proxies_list[0]
proxies = {"http": f"http://{proxy}", "https": f"http://{proxy}"}
r = requests.get("https://api.ipify.org", proxies=proxies, timeout=10)
print(r.text)
```

### cURL
```bash
curl -s https://raw.githubusercontent.com/6yyn/free-proxy-list/main/proxies.txt
curl -x http://IP:PORT https://api.ipify.org
```

---

## 💎 Premium

For **dedicated IPs**, **99.9% uptime**, and **high-speed** access:

| Plan | Price | Duration |
|------|-------|----------|
| Trial | $3 | 24 hours |
| Weekly | $11 | 7 days |
| Bi-Weekly | $18 | 14 days |
| Monthly | $29 | 30 days |

👉 [Contact on Telegram](https://t.me/w57n1) | 🌐 [Website](https://free.6yyn.shop)

---

## 🔗 Links

- 🌐 [Website](https://free.6yyn.shop)
- 📢 [Telegram Channel](https://t.me/KWKKH)
- 💎 [Premium Contact](https://t.me/w57n1)

---

## ⚠️ Notes

- Use responsibly.
- Free proxies are shared — expect slower speeds.

---

**© 2026 6YYN - All Rights Reserved**
