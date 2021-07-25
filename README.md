# New update from AMD machine

# Notes for git:

## Git pull (clone project to new local)

```
git init
git remote add origin git@github.com:tam-nt24897/react-crash-course-2021.git
git pull origin main
```

### Check if not set
```
git config --global user.email “you@example.com”
git config --global user.name “Your Name”
```

### Check list of config
#### `git config --list`

## Push an existing repository from the command line

```
git remote add origin git@github.com:tam-nt24897/sad.git
git branch -M main
git push -u origin main
```

## For the new "main" branch as default, you can do this way:

```
git checkout master
git branch main master -f
git checkout main
git push origin main -f
```

---

# Notes to run app

## 1. Start server

### `npm run server`

## 2. Start project

### `npm start`

# Some library is used

### `react-router-dom , json-server , react-icons`

---

07/25/2021
