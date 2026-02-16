# v2rayCollector

Automatically collects public **V2Ray-compatible proxies** from various web sources, combines them, tests them, and commits the results to this repository.

Supported proxy types:

`VMess` • `VLess` • `Trojan` • `Shadowsocks` • `Hysteria2` • `Tuic` • `Socks` • `Http`

Subscriptions are automatically updated.

Proxy testing is performed using **[Sing-box](https://github.com/SagerNet/sing-box)**.

---

## 📌 How It Works

1. Proxies are collected from multiple public web sources.
2. They are merged and deduplicated.
3. Each proxy is tested (TCP, URL, and speed tests).
4. Working proxies are grouped by ISP.
5. Results are committed automatically to this repository.

---

## 🚀 Usage

Simply import the subscription link corresponding to your ISP and test type into your preferred client (e.g., v2rayNG, V2RayN, Clash, Hiddify, Sing-box, etc.).

---

## 📡 Available Subscriptions

### ☁️ RouterHosting LLC  ·  cloudzy (AS14956)

* **TCP Test**
  [https://raw.githubusercontent.com/sorenadev-dev/v2rayCollector/refs/heads/main/sub/tcp-cloudzy.txt](https://raw.githubusercontent.com/sorenadev-dev/v2rayCollector/refs/heads/main/sub/tcp-cloudzy.txt)

* **URL Test**
  [https://raw.githubusercontent.com/sorenadev-dev/v2rayCollector/refs/heads/main/sub/url-cloudzy.txt](https://raw.githubusercontent.com/sorenadev-dev/v2rayCollector/refs/heads/main/sub/url-cloudzy.txt)

* **Speed Test**
  [https://raw.githubusercontent.com/sorenadev-dev/v2rayCollector/refs/heads/main/sub/speed-cloudzy.txt](https://raw.githubusercontent.com/sorenadev-dev/v2rayCollector/refs/heads/main/sub/speed-cloudzy.txt)

---

### 🌐 Aria Shatel PJSC (AS31549)

* **TCP Test**
  [https://raw.githubusercontent.com/sorenadev-dev/v2rayCollector/refs/heads/main/sub/tcp-shatel.txt](https://raw.githubusercontent.com/sorenadev-dev/v2rayCollector/refs/heads/main/sub/tcp-shatel.txt)

* **URL Test**
  [https://raw.githubusercontent.com/sorenadev-dev/v2rayCollector/refs/heads/main/sub/url-shatel.txt](https://raw.githubusercontent.com/sorenadev-dev/v2rayCollector/refs/heads/main/sub/url-shatel.txt)

* **Speed Test**
  [https://raw.githubusercontent.com/sorenadev-dev/v2rayCollector/refs/heads/main/sub/speed-shatel.txt](https://raw.githubusercontent.com/sorenadev-dev/v2rayCollector/refs/heads/main/sub/speed-shatel.txt)

---

### 🏢 ANDISHE SABZ KHAZAR CO. P.J.S. (AS39308)

* **TCP Test**
  [https://raw.githubusercontent.com/sorenadev-dev/v2rayCollector/refs/heads/main/sub/tcp-andishe.txt](https://raw.githubusercontent.com/sorenadev-dev/v2rayCollector/refs/heads/main/sub/tcp-andishe.txt)

* **URL Test**
  [https://raw.githubusercontent.com/sorenadev-dev/v2rayCollector/refs/heads/main/sub/url-andishe.txt](https://raw.githubusercontent.com/sorenadev-dev/v2rayCollector/refs/heads/main/sub/url-andishe.txt)

* **Speed Test**
  [https://raw.githubusercontent.com/sorenadev-dev/v2rayCollector/refs/heads/main/sub/speed-andishe.txt](https://raw.githubusercontent.com/sorenadev-dev/v2rayCollector/refs/heads/main/sub/speed-andishe.txt)

---

## 🧪 Test Types Explained

* **TCP Test** – Checks basic connectivity to the proxy endpoint.
* **URL Test** – Tests real HTTP access through the proxy.
* **Speed Test** – Measures download throughput for performance ranking.

---

## ⚠️ Disclaimer

This repository aggregates publicly available proxy configurations.
Availability and performance may vary.
Use at your own discretion and comply with local laws and regulations.

---

If you want, I can also:

* Add GitHub badges (auto-update, workflow status, last commit)
* Add architecture diagram section
* Add automation/workflow explanation (GitHub Actions)
* Add contribution guidelines
* Make it more SEO-friendly
* Or rewrite it in a more minimal/clean hacker-style format
