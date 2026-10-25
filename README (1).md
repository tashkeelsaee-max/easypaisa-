# SabzPay Wallet (Demo)

Ek **practice / learning** mobile-wallet UI jo EasyPaisa-style dashboard ki tarah banaya gaya hai.
Pura app ek single `index.html` file mein hai — koi build, koi dependency, koi server nahi chahiye.

> ⚠️ Ye sirf seekhne ke liye ek demo hai. Iska EasyPaisa ya kisi real service se koi taalluq nahi, aur isme koi real paisa ya real login involve nahi hota. Saara data dummy hai.

## Features

- **Login** — koi bhi number + 4-digit PIN (pehle se bhara hua)
- **Dashboard** — account card, balance, Hide/Show balance, horizontal cards (Account + Borrow)
- **Services grid** — Send Money, Bill Payment, Loads & Packages, Easycash, aur zyada
- **Send Money** — recipient, number, amount (quick-amount chips)
- **Loads & Packages** — Jazz / Zong / Telenor / Ufone / Onic
- **Bill Payment** — bijli, gas, pani, internet, TV, fee
- **Add Money** — bank / card se wallet top-up
- **Transaction History** — har transaction balance update karti hai
- **Stories** + bottom navigation (Home / Cards / Pay / Promotions / Zen)
- Balance aur transactions browser ke `localStorage` mein save rehte hain
- Light aur dark dono themes

## Kaise chalayein

Bas `index.html` ko browser mein khol lein — ya GitHub Pages par host kar dein.

### GitHub par daalne ke steps

```bash
git init
git add index.html README.md
git commit -m "SabzPay wallet demo"
git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```

Phir repo → **Settings → Pages** mein branch `main` select karein. Thodi der baad aapka link live ho jayega:
`https://<username>.github.io/<repo>/`

## Tech

Plain HTML, CSS aur vanilla JavaScript. Koi framework nahi.

## License

MIT — jaise chahein use karein.
