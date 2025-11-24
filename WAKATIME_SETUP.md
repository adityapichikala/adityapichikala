# 🕐 WakaTime Setup Guide

## Your WakaTime API Key
```
waka_xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx
```

---

## 🔐 IMPORTANT: Add to GitHub Secrets

⚠️ **DO NOT commit this API key directly to your repository!**

### Step-by-Step Instructions:

1. **Go to Your Repository on GitHub**
   - Visit: https://github.com/adityapichikala/adityapichikala

2. **Navigate to Settings**
   - Click on **Settings** tab at the top

3. **Go to Secrets and Variables**
   - In the left sidebar, click **Secrets and variables** → **Actions**

4. **Add New Secret**
   - Click **New repository secret** button
   - Name: `WAKATIME_API_KEY`
   - Value: `your_wakatime_api_key`
   - Click **Add secret**

---

## ✅ What This Enables

Once the secret is added, your GitHub Actions workflow will:
- ✅ Update your coding stats **daily**
- ✅ Show languages you've been coding in
- ✅ Display time spent coding
- ✅ Track your weekly development activity

The stats will appear in your README under the "Weekly Development Breakdown" section!

---

## 📥 Install WakaTime Plugin

To start tracking your coding time:

### VS Code
1. Open VS Code
2. Go to Extensions (Ctrl+Shift+X)
3. Search for "WakaTime"
4. Click Install
5. Enter your API key when prompted

### PyCharm / IntelliJ
1. Go to Settings → Plugins
2. Search for "WakaTime"
3. Install and restart
4. Enter API key in WakaTime settings

### Other IDEs
Visit: https://wakatime.com/plugins

---

## 🧪 Test the Workflow

After adding the secret:

1. **Go to Actions Tab**
   - Visit: https://github.com/adityapichikala/adityapichikala/actions

2. **Find "Waka Readme" Workflow**
   - Click on "Waka Readme"

3. **Run Manually**
   - Click **Run workflow** → **Run workflow**

4. **Wait for Completion**
   - Should complete in ~30 seconds

5. **Check Your README**
   - Stats should appear in the WakaTime section!

---

## 📊 Expected Output

After 24 hours of coding with WakaTime plugin active, your README will show:

```
📊 Weekly Development Breakdown

Python       8 hrs 30 mins  ████████████░░░  45.2%
JavaScript   4 hrs 15 mins  ██████░░░░░░░░░  22.5%
TypeScript   3 hrs 20 mins  █████░░░░░░░░░░  17.8%
SQL          1 hr 45 mins   ██░░░░░░░░░░░░░   9.3%
Other        1 hr 0 mins    █░░░░░░░░░░░░░░   5.2%
```

---

## 🎯 Quick Checklist

- [ ] WakaTime API key added to GitHub Secrets
- [ ] WakaTime plugin installed in your IDE
- [ ] API key entered in plugin settings
- [ ] Start coding to generate stats!
- [ ] Wait 24 hours for first update
- [ ] Check your profile for stats

---

## 🔒 Security Note

✅ **Correct**: API key stored in GitHub Secrets
❌ **Wrong**: API key in code files or README

GitHub Secrets are encrypted and only accessible to GitHub Actions workflows. Never commit API keys directly to your repository!

---

**Your WakaTime integration is ready! Start coding and watch your stats appear!** 🚀
