# Adding Your Profile Image

## Option 1: Upload Image to Repository (Recommended)

1. **Rename your image file** to `profile.jpg` (or `profile.png`)

2. **Upload to the repository** - You can do this in two ways:

   ### Via GitHub Web Interface:
   - Go to https://github.com/iSpammer/portfolio
   - Click "Add file" → "Upload files"
   - Drag and drop your `profile.jpg` file
   - Commit the changes

   ### Via Command Line:
   ```bash
   cd /home/ispamr/portofolio
   # Copy your image from Windows to WSL (adjust path as needed)
   cp "/mnt/c/Users/OsamaHussien/Downloads/temp_image_20240902_145025_918f4042-a61e-4b02-96dc-45e9348f36e7 (1).jpg" profile.jpg

   git add profile.jpg
   git commit -m "Add profile image"
   git push origin main
   ```

3. The website will automatically display your image!

## Option 2: Use External Image URL

If you prefer to host your image elsewhere (LinkedIn, Google Drive, etc.):

1. Upload your image to an image hosting service
2. Get the direct image URL
3. Edit `index.html` and replace:
   ```html
   <img src="profile.jpg" alt="Osama Hussien" class="profile-image"
   ```
   with:
   ```html
   <img src="YOUR_IMAGE_URL_HERE" alt="Osama Hussien" class="profile-image"
   ```

## Current Behavior

- The website currently shows a generated avatar with your initials
- Once you add `profile.jpg`, it will automatically replace the fallback avatar
- The image will be displayed as a 200x200px circular profile picture
- It has a nice blue border and hover animation

## Image Specifications

- **Recommended size**: At least 400x400px (for retina displays)
- **Format**: JPG, PNG, or WebP
- **File size**: Keep under 500KB for fast loading
- **Aspect ratio**: Square (1:1) works best

## Need Help?

The image location in the HTML is at line ~980 in the About Section.
