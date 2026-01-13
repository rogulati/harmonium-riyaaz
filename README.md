# My Harmonium Learning Journey 🎹

A personal website documenting my journey learning the Harmonium and Indian classical music.

## Website Structure

The site contains the following pages:

1. **Home** (index.html) - Main landing page with navigation
2. **Basics (Youtube)** - Collection of YouTube learning resources
3. **AKHIL BHARATIYA GANDHARVA** - Information about the music institution
4. **Harmonium Basics** - Fundamental techniques and posture
5. **Definitions** - Musical terminology and concepts
6. **Alankaars** - Musical exercises and patterns
7. **Songs** - Personal repertoire of songs being learned
8. **Thaats** - The 10 parent scales of Hindustani music
9. **Taal** - Rhythmic cycles and patterns
10. **Raag** - Melodic frameworks being studied

## Deploying to GitHub Pages

Follow these steps to publish your site on GitHub Pages:

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in to your account (rogulati)
2. Click the **+** icon in the top right and select **New repository**
3. Name your repository: `rogulati.github.io` (for user site) or `harmonium-journey` (for project site)
4. Set it to **Public**
5. Do NOT initialize with README (we already have files)
6. Click **Create repository**

### Step 2: Initialize Git and Push Your Files

Open a terminal in the `learnsite` folder and run these commands:

```powershell
# Initialize git repository
git init

# Add all files
git add .

# Commit the files
git commit -m "Initial commit - Harmonium learning journey website"

# Add your GitHub repository as remote
# For user site (rogulati.github.io):
git remote add origin https://github.com/rogulati/rogulati.github.io.git

# OR for project site (harmonium-journey):
# git remote add origin https://github.com/rogulati/harmonium-journey.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** tab
3. Click **Pages** in the left sidebar
4. Under **Source**, select **main** branch
5. Select **/ (root)** folder
6. Click **Save**

### Step 4: Access Your Site

After a few minutes, your site will be available at:

- **User site**: https://rogulati.github.io/
- **Project site**: https://rogulati.github.io/harmonium-journey/

## Local Development

To view your site locally before pushing to GitHub:

1. Open `index.html` in your web browser
2. Navigate through the pages to test all links

## Updating Your Site

Whenever you make changes:

```powershell
git add .
git commit -m "Description of your changes"
git push
```

GitHub Pages will automatically update within a few minutes.

## Customization Tips

- **Add your content**: Replace placeholder text with your actual learning notes
- **Add images**: Create an `images/` folder and add photos of your harmonium, musical notation, etc.
- **Modify colors**: Edit `style.css` to change the color scheme
- **Add more pages**: Create new HTML files following the same template structure

## Technologies Used

- HTML5
- CSS3
- No JavaScript (simple and fast!)
- GitHub Pages for hosting

## License

This is a personal learning journal. Feel free to use the template for your own journey!

---

Last updated: January 2026
