# Cleaning Up Personal Content

This guide will help you remove the original author's personal content from this repository before using it as your own template.

## Files to Remove

Before customizing the template with your own content, you should remove or replace these personal files:

### 1. Personal Images

Remove all the original images from the `images` directory except for placeholder files:
```bash
# Backup the placeholders and README
mkdir -p temp_backup
cp images/README.md temp_backup/
cp images/project1_before.jpg temp_backup/
cp images/project1_after.jpg temp_backup/
cp images/YourPhoto.jpg temp_backup/

# Remove all original images
rm -rf images/*

# Restore placeholders
mkdir -p images/favicon
cp temp_backup/* images/
rm -rf temp_backup
```

### 2. Personal Data Files

Remove all the original data files:
```bash
# Backup your placeholder content
mkdir -p temp_backup
cp data/YourName-bio.txt temp_backup/

# Remove all original data files
rm -rf data/*

# Restore placeholders
cp temp_backup/* data/
rm -rf temp_backup
```

### 3. Project-Specific Folders

Remove project-specific folders that aren't needed:
```bash
rm -rf mipnerf*
rm -rf zipnerf
rm -rf papers
```

### 4. Clean Up Git History (Optional)

If you want to completely remove the Git history:
```bash
rm -rf .git
git init
git add .
git commit -m "Initial commit with clean template"
```

## Using the Clean Template

After cleaning up, you can:

1. Copy the template HTML file to the main index.html:
```bash
cp templates/index_template.html index.html
```

2. Follow the instructions in the README.md to customize the template with your content

3. Add your images to the `images` directory

4. Add your documents to the `data` directory

5. Commit your changes and push to GitHub

## Testing Your Website Locally

Before pushing to GitHub, you can test your website locally:
```bash
# Using Python's built-in HTTP server
python -m http.server

# Or if you have Node.js installed
npx serve
```

Then open your browser to http://localhost:8000 (or the port indicated in the command output). 