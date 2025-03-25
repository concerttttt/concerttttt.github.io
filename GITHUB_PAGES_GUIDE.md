# Hosting Your Website on GitHub Pages

This guide will help you set up your personal website on GitHub Pages using this template.

## Step 1: Set Up Your Repository

There are two approaches:

### Option A: Create a New Repository

1. Create a new GitHub repository named `yourusername.github.io` (replace "yourusername" with your actual GitHub username)
2. Clone this repository to your local machine
3. Add the files from this template to your local repository
4. Commit and push the changes to GitHub

### Option B: Fork This Repository

1. Fork this repository to your GitHub account
2. Rename the forked repository to `yourusername.github.io`
3. Clone your fork to your local machine
4. Customize the template as needed
5. Commit and push the changes to GitHub

## Step 2: Customize the Template

1. Edit `index.html` to replace all placeholder content with your information
2. Replace the placeholder images in the `images` directory
3. Add your CV, bio, and other documents to the `data` directory
4. Make any desired styling changes to `stylesheet.css`

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" (tab with a gear icon)
3. Scroll down to the "GitHub Pages" section
4. Under "Source", select the branch you want to use (usually "main" or "master")
5. Click "Save"
6. GitHub will provide a URL where your site is published (it may take a few minutes to become available)

## Step 4: Using a Custom Domain (Optional)

If you want to use your own domain instead of yourusername.github.io:

1. Add a file named `CNAME` to your repository root
2. Inside the file, add your domain name (e.g., `example.com`)
3. Configure your domain's DNS settings:
   - Create an A record pointing to GitHub Pages IP addresses:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - Or create a CNAME record pointing to `yourusername.github.io`
4. In your repository settings, enter your custom domain in the "GitHub Pages" section
5. Check "Enforce HTTPS" if desired (recommended)

## Troubleshooting

- **Site not appearing**: It can take up to 10 minutes for changes to publish
- **Custom domain not working**: DNS changes can take 24-48 hours to propagate
- **CSS not loading**: Make sure file paths are correct in your HTML files

## Additional Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Setting up a custom domain with GitHub Pages](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)
- [HTTPS for custom domains](https://docs.github.com/en/pages/getting-started-with-github-pages/securing-your-github-pages-site-with-https) 