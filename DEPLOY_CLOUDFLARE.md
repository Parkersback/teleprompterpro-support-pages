# Deploy to Cloudflare Pages (TeleprompterPro)

Current repo:
- https://github.com/Parkersback/teleprompterpro-support-pages

## 1) Login (once)
```bash
wrangler login
```

## 2) Create Pages project (first time only)
```bash
cd /Users/jian/.openclaw/workspace/teleprompterpro-support-pages
npx wrangler pages project create teleprompterpro-support-pages --production-branch main
```

## 3) Deploy
```bash
cd /Users/jian/.openclaw/workspace/teleprompterpro-support-pages
npx wrangler pages deploy . --project-name teleprompterpro-support-pages
```

## 4) URLs for App Store Connect
- Support URL: `https://teleprompterpro-support-pages.pages.dev/support.html`
- Privacy URL: `https://teleprompterpro-support-pages.pages.dev/privacy.html`

If you bind a custom domain in Cloudflare, replace the URLs above with your domain.
