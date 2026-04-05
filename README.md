# THE AI MEDIA COMPANY

Built with Toy and KiloClaw.

## 🚀 Quick Deploy to Cloudflare Pages

### 1. Fork/Clone This Repo

```bash
git clone https://github.com/toyeiei/ai-media-company.git
cd ai-media-company
```

### 2. Connect to Cloudflare Pages

1. Go to [Cloudflare Dashboard](https://dash.cloudflare.com) → Pages
2. Connect to GitHub → Select `ai-media-company` repo
3. Settings:
   - **Project name:** `ai-media-company`
   - **Production branch:** `main`
   - **Build output directory:** `/blog` (or leave blank for root)
4. Click **Save and Deploy**

### 3. Set Up Secrets (for auto-deploy)

In your GitHub repo → Settings → Secrets and variables → Actions, add:

| Secret | Where to Find |
|--------|---------------|
| `CLOUDFLARE_API_TOKEN` | Cloudflare Profile → API Tokens → Create Token (Use "Edit Cloudflare Pages" template) |
| `CLOUDFLARE_ACCOUNT_ID` | Cloudflare Dashboard → Overview (bottom right corner shows Account ID) |

### 4. That's It! ✅

Every time you push to `main`, Cloudflare Pages will auto-deploy!

---

## 📝 Adding New Content

Edit `blog/index.html` and add your content to the JavaScript array:

```javascript
{
    title: "Your Post Title",
    date: "2026-04-05",
    excerpt: "Your post description...",
    platform: "LinkedIn",
    url: "https://your-link.com"
}
```

Then commit and push:

```bash
git add .
git commit -m "Add new content"
git push origin main
```

---

## 🎨 Design

- **Font:** JetBrains Mono
- **Colors:** Dark theme with green accent (#00ff88)
- **Style:** Minimal, card-based layout

---

## 🤖 Powered By

- **KiloClaw** - AI orchestration
- **Discord** - Command center
- **Paperclip** - AI company management

---

THE AI MEDIA COMPANY © 2026
