# Attendance Tracker - Expo App

## GitHub se APK banane ke steps:

### Step 1: Expo Account banao
1. https://expo.dev pe jaao
2. Sign up karo (free)

### Step 2: EXPO_TOKEN lo
1. https://expo.dev/accounts/[username]/settings/access-tokens
2. "Create Token" click karo
3. Token copy karke rakho

### Step 3: GitHub repo banao
1. https://github.com/new pe jaao
2. Repo name: `attendance-tracker`
3. Private rakh sakte ho
4. Create repository

### Step 4: GitHub Secret add karo
1. Repo → Settings → Secrets and variables → Actions
2. "New repository secret" click karo
3. Name: `EXPO_TOKEN`
4. Value: expo token paste karo
5. Save

### Step 5: Files upload karo
Yeh saari files GitHub repo mein upload karo:
- App.js
- app.json
- package.json
- babel.config.js
- eas.json
- .gitignore
- assets/app.html
- .github/workflows/build-apk.yml

### Step 6: Build trigger karo
- Files push karte hi build automatically start ho jaayega
- Ya GitHub repo → Actions → "Build APK" → "Run workflow"

### Step 7: APK download karo
- Build 10-15 min mein complete hoga
- https://expo.dev pe login karo → Projects → attendance-tracker → Builds
- APK download karo aur install karo!

## Local test karna hai? (agar kabhi laptop mile)
```bash
npm install
npx expo start
```
Expo Go app se QR scan karo.
