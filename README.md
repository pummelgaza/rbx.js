# rbx.js

**rbx.js** is an actively maintained and modernized continuation of the popular Roblox Node.js library **https://github.com/noblox/noblox.js**.

It is built using the original noblox.js source as a foundation, with improvements, updates, and ongoing maintenance to ensure compatibility with current Roblox API changes and Node.js environments.

---

## ⚠️ Important Notice

rbx.js is **not an official Roblox library** and is **not affiliated with Roblox Corporation**.

This project is:
- Based on the original noblox.js source
- Updated and maintained independently
- Designed to keep the ecosystem alive with modern fixes and improvements

---

## ✨ Features

- Full Roblox Web API support  
- Cookie-based authentication  
- Group management utilities  
- User & group data fetching  
- Shout, rank, and role tools  
- Lightweight and easy to use  
- Actively maintained with updates  

---

## 📦 Installation

```bash
npm install rbx.js
```

---

## 🚀 Example Usage

```js
const rbx = require("rbx.js");

(async () => {
    await rbx.setCookie("YOUR_ROBLOSECURITY_COOKIE");

    const user = await rbx.getCurrentUser();
    console.log(user);
})();
```

---

## 🔄 Relationship to noblox.js

rbx.js is directly inspired by and built upon **noblox.js**.

- Uses noblox.js as the original source foundation  
- Refactored and maintained for modern compatibility  
- Updated to fix deprecated endpoints and improve stability  
- Continues development independently to ensure long-term support  

We greatly respect the original work of the noblox.js contributors.

---

## 📚 Documentation

Documentation will be added soon.

Most noblox.js functions remain compatible unless otherwise stated.

---

## ⚖️ License

This project follows the same open-source spirit as noblox.js.

---

## 🙏 Credits

- Original library: https://github.com/noblox/noblox.js  
- All contributors of noblox.js  
- Community maintainers of rbx.js
