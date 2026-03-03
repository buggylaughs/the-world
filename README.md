# 🌍 The World — In a Folder

> **197 countries. 6 continents. 1 Git command to get it. 1 command to delete it forever.**

This repository contains a folder called `world/` with every country on Earth organized by continent. Each country is a `.txt` file with its capital, population, area, and currency.

---

## 📂 Folder Structure

```
world/
├── Africa/          (54 countries)
├── Asia/            (49 countries)
├── Europe/          (45 countries)
├── North_America/   (23 countries)
├── South_America/   (12 countries)
└── Oceania/         (14 countries)
```

Each file looks like this:

```
Country:    India
Continent:  Asia
Capital:    New Delhi
Population: 1,380,004,385
Area:       3,287,263 km2
Currency:   Indian Rupee
```

---

## 🚀 Getting Started

### Step 1 — Install Git

- **Windows**: Download from [git-scm.com](https://git-scm.com/download/win) and install
- **Mac**: Run `xcode-select --install` in Terminal
- **Linux**: Run `sudo apt install git`

Verify it worked:
```bash
git --version
```

---

### Step 2 — Clone this Repository

Open Command Prompt (Windows) or Terminal (Mac/Linux) and run:

```bash
git clone https://github.com/buggylaughs/the-world.git
```

Then go into the folder:
```bash
cd the-world
```

You now have the entire world on your computer. 🌍

---

### Step 3 — Explore the World

List all continents:
```bash
ls world/
```

Look inside a continent:
```bash
ls world/Asia/
```

Read a country:
```bash
cat world/Asia/India.txt
```

---

### ☠️ Step 4 — Delete the World

**Mac/Linux:**
```bash
rm -rf world/
```

**Windows (Command Prompt):**
```cmd
rmdir /s /q world
```

**Windows (PowerShell):**
```powershell
Remove-Item -Recurse -Force world
```

The entire world is gone. 197 files. Deleted. Just like that.

---

### 🔁 Step 5 — Bring it Back

```bash
git checkout .
```

And just like that — the world is restored. That's the power of Git.

---

## 💡 What You Learned

| Concept | Command Used |
|---|---|
| Install Git | `git --version` |
| Clone a repo | `git clone <url>` |
| Navigate folders | `cd`, `ls` / `dir` |
| Read a file | `cat` / `type` |
| Delete files | `rm -rf` / `rmdir` |
| Restore with Git | `git checkout .` |

---

## 📊 Data Source

Country data sourced from [Wikipedia — List of countries by continents](https://simple.wikipedia.org/wiki/List_of_countries_by_continents), population figures from UN World Population Prospects 2021.

---

## 🎬 Watch the Tutorial

> Link to YouTube video here

---

## ⭐ Give it a Star

If this repo helped you learn Git, drop a ⭐ — it helps more people find it!
