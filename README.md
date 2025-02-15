# Hugo Site Deployment Guide

## Publishing Changes

To publish changes to your Hugo site, follow these steps:

1. **Make changes**: Make the desired changes to your Hugo site.

2. **Build the Hugo site**: Build the Hugo site to generate the static files:

   ```bash
   hugo

3. **Navigate to the public directory:**
   ```bash
   cd public

5. **Commit and push the changes:**
   ```bash
   git add .
   git commit -m "Update Hugo site"
   git push origin main
