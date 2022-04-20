# firebase

Install firebase CLI tool:
```bash
curl -sL https://firebase.tools | bash
```

Login to your account:
```bash
firebase login
```

List the apps you have deployed:
```bash
firebase apps:list
```

List database instances:
```bash
firebase database:instances:list
```

List hosting channels:
```bash
firebase hosting:channel:list
```

List hosting sites:
```bash
firebase hosting:sites:list
```

List projects:
```bash
firebase projects:list
```
---

### Prepare NodeJS app

Install packages:
```bash
npm install
```

Build the app:
```bash
npm run build
```

Deploy the app:
```bash
firebase deploy
```
