
## Task 7 – Git Bash Practice (Phase 1 Continued)

**Objective:** Use Git commands in **Git Bash** to manage files and directories like a real developer!

---

### 🛠️ Prerequisites

✅ Git should already be installed (with Git Bash).
✅ You should have a GitHub account.
✅ You should already know the URL of the `Nebatech-phase1` repository.

---

### ✅ **Step-by-Step Instructions**

#### 1. **Open Git Bash**

* Right-click on your Desktop or inside a folder > click **Git Bash Here**
  Or search **Git Bash** in Start Menu and open it.

---

#### 2. **Navigate to a working directory (optional)**

```bash
cd Documents
mkdir nebatech-project
cd nebatech-project
```

---

#### 3. **Clone the `Nebatech-phase1` Repository**

```bash
git clone https://github.com/YOUR_USERNAME/Nebatech-phase1.git
cd Nebatech-phase1
```

---

#### 4. **Create a directory named `assets`**

```bash
mkdir assets
```

---

#### 5. **Create sub-directories: `css`, `images`, `js` inside `assets`**

```bash
cd assets
mkdir css images js
```

---

#### 6. **Move `style.css` to `assets/css`**

Make sure `style.css` is in the root directory. Then run:

```bash
mv ../style.css css/
```

---

#### 7. **Create a new file `scripts.js` in the `js` folder**

```bash
cd js
touch scripts.js
```

---

#### 8. **Clone the image repository**

I'll create a simple public GitHub repo with sample pictures. For example:

```bash
cd ../images
git clone https://github.com/IAmAbdulHafiz/images.git temp
mv temp/* .  # Move all images to the current directory
rm -rf temp  # Clean up temporary folder
```

---

#### 9. **Check your changes**

```bash
cd ../../  # Go back to project root
git status
```

---

#### 10. **Stage, commit and push**

```bash
git add .
git commit -m "Organized assets and added images & scripts.js"
git push origin main
```

Once you are done check your repository on GitHub and you will see the changes.
---

### **Recap of What You've Practiced Today:**

* Using Git commands in Git Bash
* Navigating directories
* Creating folders
* Moving and organizing files
* Cloning a second repo for assets
* Committing and pushing via command line

This is how professional developers work daily — you’re doing great!

