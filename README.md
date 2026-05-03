# RIVASILL – Rivanta Enterprises Website

A fully static website for RIVASILL silicone sealant products. No backend server needed.
Form queries are delivered directly to your email via **Web3Forms** (free service).

---

## STEP 1 — Get Your Free Web3Forms Access Key

1. Go to **https://web3forms.com/**
2. Enter your email: `sanjeevkumargautam@gmail.com`
3. Click **Create Access Key**
4. Check your email — you'll get a key like: `xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx`

---

## STEP 2 — Add Your Access Key to the Website

Open `index.html` and find this line (around line 215):

```html
<input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE" />
```

Replace `YOUR_ACCESS_KEY_HERE` with the key from your email. Example:

```html
<input type="hidden" name="access_key" value="abc12345-1234-5678-abcd-example12345" />
```

Save the file.

---

## STEP 3 — Deploy to GitHub Pages (Free)

### First time setup:

1. Go to **https://github.com** → Sign in / Create a free account
2. Click the **+** button → **New repository**
3. Name it: `rivanta-ui` (or any name)
4. Set it to **Public** ✅
5. Click **Create repository**

### Push your files:

Open **Command Prompt** or **Git Bash** in this folder and run:

```bash
git add .
git commit -m "Initial website"
git branch -M main
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/rivanta-ui.git
git push -u origin main
```

*(Replace `YOUR_GITHUB_USERNAME` with your actual GitHub username)*

### Enable GitHub Pages:

1. Go to your repo on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under **Source**, select **GitHub Actions**
4. Click **Save**

Your website will be live at:
**`https://YOUR_GITHUB_USERNAME.github.io/rivanta-ui/`**

It auto-deploys every time you push changes!

---

## STEP 4 — Receiving Queries

When someone fills the form on your website:
- You instantly receive an email at `sanjeevkumargautam@gmail.com`
- The email contains all details: name, phone, email, city, quantities, requirements
- Reply directly to the customer from your email

Web3Forms free plan: **250 submissions/month** — more than enough for a business website.

---

## Adding Product Images

Replace the placeholder image areas in `index.html` by searching for:
```
(Replace with product image)
```
And replace the `<div>` blocks with `<img>` tags pointing to your image files.

Place your product images in the same folder as `index.html`, e.g.:
- `clear-product.jpg`
- `white-product.jpg`
- `black-product.jpg`

---

## Need Help?

Contact the developer or WhatsApp +91 8447862867
