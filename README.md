# StyledWithSass

# 🚀 SCSS Setup with HTML  

Follow these simple steps to configure SCSS with HTML! 🎨✨  

## 📂 Project Structure  
```bash
/project-folder
│── /scss
│ ├── style.scss
│── /css
│ ├── style.css (Generated automatically)
│── index.html
```

## 🛠️ Setup Steps  

### 1️⃣ Install Node.js & npm (if not installed)  
👉 Download from [Node.js Official Site](https://nodejs.org/)  

### 2️⃣ Initialize the Project (Optional)  
Run the following command in the terminal:  
```bash
npm init -y
```
### Install Sass

#### Globally: 🌎
 ```bash
npm install -g sass
```
#### Locally: 📦
```bash
npm install sass --save-dev
```
### 4️⃣ Compile SCSS to CSS
⚡ Run this command to start watching SCSS changes:
```bash
sass scss/style.scss css/style.css --watch
```
- `scss/style.scss` → Input SCSS file  
- `css/style.css` → Output CSS file  
- `--watch` → Automatically compiles when SCSS changes  

