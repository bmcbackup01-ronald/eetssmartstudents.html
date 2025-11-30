# Deploy EETS Landing on GitHub Pages

## 1. Create a GitHub Repository
1. Go to https://github.com
2. Click **New Repository**
3. Name it for example:
   ```
   eets-landing
   ```
4. Choose **Public**
5. Click **Create Repository**

---

## 2. Upload the HTML file
1. Open your new repo
2. Click **Add file > Upload files**
3. Upload the file:
   - `eets_landing.html`
4. Click **Commit changes**

---

## 3. Enable GitHub Pages
1. Go to:
   **Settings > Pages**
2. Under **Build and deployment**:
   - Source: **Deploy from branch**
   - Branch: choose **main** and **/ (root)**
3. Click **Save**

After a few seconds GitHub generates your website URL:
```
https://<your-username>.github.io/eets-landing/
```

---

## 4. (Optional) Rename the file for auto-loading
Rename `eets_landing.html` to:
```
index.html
```
Because GitHub Pages only auto-loads `index.html`.

---

## 5. Update your site anytime
Just push a new commit or upload a new version.
GitHub Pages refreshes automatically.

---

## Done 🎉
Now your EETS landing page is live on the web.