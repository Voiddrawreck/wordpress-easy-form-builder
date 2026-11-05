# 📝 WordPress Easy Form Builder

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=13,5,18&height=210&section=header&text=WordPress%20Easy%20Form%20Builder&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Beautiful%20Forms%20in%20Minutes%2C%20No%20Code%20Required&descAlignY=56&descSize=17" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-3.7.0-2176AE?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![WordPress](https://img.shields.io/badge/WordPress-6.4+-57A773?style=for-the-badge&logo=wordpress&logoColor=white)](https://wordpress.org)
[![License](https://img.shields.io/badge/license-GPL--2.0-FF7B9C?style=for-the-badge&logo=gnu&logoColor=white)](LICENSE)
[![Fields](https://img.shields.io/badge/fields-30%2B-FFC4D6?style=for-the-badge&logo=wpforms&logoColor=black)](https://github.com)

<br/>

### 🎨 A drag-and-drop form builder plugin for WordPress — powerful, fast & beginner-friendly

*🖱️ Drag & Drop • 📧 Email Notifications • 📱 Responsive • 🔌 Integrations*

<br/>

<a href="https://share.google/8Fnb3Io6oeKk01UIH">
  <img src="https://img.shields.io/badge/📥_DOWNLOAD_PLUGIN-2176AE?style=for-the-badge&logo=wordpress&logoColor=white&labelColor=175683" alt="Download Plugin" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/8Fnb3Io6oeKk01UIH">
  <img src="https://img.shields.io/badge/🚀_LIVE_DEMO-57A773?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=3E7B54" alt="Live Demo" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/8Fnb3Io6oeKk01UIH">
  <img src="https://img.shields.io/badge/📚_DOCS-FF7B9C?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=CC5C7A" alt="Docs" height="45"/>
</a>

</div>

<img width="1544" height="500" alt="banner-1544x500" src="https://github.com/user-attachments/assets/96f6e710-2c5e-4f1f-9904-4ab4c9f5e7c9" />

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**WordPress Easy Form Builder** is a **lightweight, no-code form plugin** that lets you create beautiful, functional forms in minutes — right from your WordPress dashboard. Drag fields onto the canvas, configure settings, embed the form anywhere with a shortcode or block, and start collecting submissions.

No coding. No bloated plugin installs. No monthly subscription. Just powerful forms that work.

> 💡 **Perfect for:** Contact forms, surveys, event registrations, lead capture, feedback forms, and any other form your WordPress site needs.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 🖱️ **Drag & Drop** | 🧩 **30+ Fields** | 📧 **Notifications** |
|:---:|:---:|:---:|
| Visual builder with<br/>live preview | Text, email, select,<br/>file upload, rating & more | Email alerts for admin<br/>& auto-reply for users |

| 📱 **Responsive** | 🛡️ **Anti-Spam** | 🔌 **Integrations** |
|:---:|:---:|:---:|
| Perfect on mobile,<br/>tablet & desktop | Honeypot + reCAPTCHA<br/>support | Mailchimp, Zapier,<br/>Webhooks & more |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Plugin

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| 🎯 **Truly No-Code** | Build any form visually — no HTML, CSS, or PHP required |
| ⚡ **Blazing Fast** | Zero bloat, minimal JS — keeps your site snappy |
| 🎨 **Theme-Friendly** | Inherits your theme's styles by default; customize everything |
| 🗂️ **Entry Management** | Browse, filter, and export submissions from the dashboard |
| 🔐 **Security First** | Nonces, sanitization, CSRF protection, and anti-spam out of the box |
| 🌍 **Translation-Ready** | Full i18n support — works in any language |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Builder Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  📝  Easy Form Builder  v3.7.0                   ║
╠══════════════════════════════════════════════════╣
║  Form: "Contact Us"                              ║
║  ──────────────────────────────────────────      ║
║  ┌──────────────┬─────────────────────────────┐  ║
║  │ 📚 Fields    │  🎨 Canvas                  │  ║
║  │ ─────────    │  ─────────                  │  ║
║  │ 📝 Text      │  [ Name            ]        │  ║
║  │ ✉️  Email     │  [ Email           ]        │  ║
║  │ 📄 Textarea  │  [ Message         ]        │  ║
║  │ 🔽 Select    │                             │  ║
║  │ ☑️  Checkbox  │  [ ✉️ Submit ]              │  ║
║  │ 📎 File      │                             │  ║
║  │ ⭐ Rating    │  ✅ 5 fields • Responsive   │  ║
║  └──────────────┴─────────────────────────────┘  ║
║                                                  ║
║  📋 Shortcode: [easy_form id="42"]               ║
║  📊 Entries: 128   ⚡ Spam blocked: 12           ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
📝 wordpress-easy-form-builder/
├── 🎯 includes/
│   ├── admin/                 # Admin settings & UI
│   │   ├── builder.php
│   │   └── entries.php
│   ├── frontend/              # Form rendering
│   │   ├── form-renderer.php
│   │   └── assets/
│   ├── fields/                # Field type classes
│   │   ├── text.php
│   │   ├── email.php
│   │   └── file.php
│   └── integrations/          # Mailchimp, Zapier, Webhooks
├── 🎨 assets/                 # CSS & JS
├── 🌍 languages/              # Translation files
├── 🧪 tests/                  # PHPUnit tests
└── 📖 readme.txt              # WordPress.org readme
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Gutenberg](https://img.shields.io/badge/Gutenberg-000000?style=for-the-badge&logo=wordpress&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a bug? Want a new field type or integration?

<div align="center">

<a href="https://share.google/8Fnb3Io6oeKk01UIH">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/8Fnb3Io6oeKk01UIH">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-2176AE?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/8Fnb3Io6oeKk01UIH">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-FF7B9C?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **GPL-2.0 License**. See [`LICENSE`](LICENSE) for details.

> **Note:** WordPress is a registered trademark of the **WordPress Foundation**. This plugin is an **independent community project** and is **not officially affiliated with or endorsed by** WordPress, Automattic, or the WordPress Foundation.

<br/>

<div align="center">

### 📝 Made with 🎨 by the Easy Form Builder Team

*If this plugin saved you from buying a form subscription — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=13,5,18&height=120&section=footer" width="100%"/>

</div>
