# Custom Domain Setup for AG Graphics Production

## Overview
This repository is configured for GitHub Pages with a custom domain using the CNAME file.

## Current CNAME Configuration
The CNAME file currently contains: `www.aggraphics.com`

**IMPORTANT:** This is a placeholder domain. To make your website live with a custom domain, you need to:

1. **Purchase or Register a Domain** (You must own the domain first)
2. **Configure DNS Settings**
3. **Update the CNAME file if needed**

---

## Step 1: Get a Custom Domain

### Option A: Free Domain Providers (Limited Options)
- **Freenom** (https://www.freenom.com) - Offers free .tk, .ml, .ga, .cf, .gq domains
  - Note: Free domains may have limitations and less professional appearance
  
### Option B: Paid Domain Registrars (Recommended)
- **Namecheap** (https://www.namecheap.com) - $8-15/year
- **Porkbun** (https://porkbun.com) - $8-12/year
- **Squarespace Domains** (https://domains.squarespace.com) - $12-20/year
- **GoDaddy** (https://www.godaddy.com) - $10-20/year

**Recommended domains for AG Graphics Production:**
- aggraphics.com
- aggraphicsproduction.com
- ag-graphics.com
- aggraphicstx.com

---

## Step 2: Configure DNS Settings

Once you have your domain, configure these DNS records with your domain registrar:

### For Apex Domain (example: aggraphics.com)

Add **A Records** pointing to GitHub Pages IPs:
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

### For WWW Subdomain (example: www.aggraphics.com)

Add a **CNAME Record**:
```
Type: CNAME
Host: www
Value: lekedada.github.io
```

### Example DNS Configuration:

| Type  | Host | Value                | TTL  |
|-------|------|----------------------|------|
| A     | @    | 185.199.108.153      | 3600 |
| A     | @    | 185.199.109.153      | 3600 |
| A     | @    | 185.199.110.153      | 3600 |
| A     | @    | 185.199.111.153      | 3600 |
| CNAME | www  | lekedada.github.io   | 3600 |

---

## Step 3: Update CNAME File (If Needed)

If you purchased a different domain than `www.aggraphics.com`, edit the `CNAME` file:

1. Navigate to the repository
2. Edit the `CNAME` file
3. Replace `www.aggraphics.com` with your actual domain
4. Commit and push the changes

**Examples:**
- If you want to use: `www.yourdomain.com` → Put: `www.yourdomain.com` in CNAME
- If you want to use: `yourdomain.com` → Put: `yourdomain.com` in CNAME
- If you want to use a subdomain: `graphics.yourdomain.com` → Put: `graphics.yourdomain.com` in CNAME

---

## Step 4: Enable HTTPS in GitHub Settings

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Custom domain", enter your domain
4. Check **"Enforce HTTPS"** (may take a few minutes to become available)

---

## Current Status: Using GitHub Pages Default URL

**Your website is currently live at:**
https://lekedada.github.io/AG-Graphics-Production/

This URL works immediately without any custom domain setup.

---

## Testing Your Setup

After configuring DNS (can take 24-48 hours for full propagation):

1. Visit your custom domain in a browser
2. Verify it loads your website
3. Test both `http://` and `https://` versions
4. Check that `www` and non-`www` versions work

### DNS Propagation Check Tools:
- https://dnschecker.org
- https://www.whatsmydns.net

---

## Troubleshooting

### "Domain not verified" error
- Wait 24-48 hours for DNS propagation
- Double-check DNS records match exactly
- Ensure CNAME file has correct domain

### Website not loading on custom domain
- Verify DNS records are correct
- Clear browser cache
- Try incognito/private browsing mode
- Wait for DNS propagation (up to 48 hours)

### SSL Certificate errors
- GitHub provides free SSL via Let's Encrypt
- May take up to 24 hours after DNS verification
- Ensure "Enforce HTTPS" is enabled in GitHub Pages settings

---

## Need Help?

If you're stuck with domain setup:
1. Check GitHub Pages documentation: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
2. Contact your domain registrar's support for DNS help
3. Check DNS propagation status with online tools

---

## What's Already Done

✅ CNAME file created with suggested domain
✅ GitHub Pages workflow configured (Jekyll)
✅ Website files ready and functional
✅ CSS and JavaScript files created
✅ Responsive design implemented

**Next Step:** Purchase/register your chosen domain and follow the DNS configuration steps above.
