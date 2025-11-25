# How to Add Your Profile Photo

## Your Current Profile Image

A placeholder image with your initials "OH" has been added temporarily.

## Replace with Your Actual Photo

### Quick Method (Using WSL):

```bash
cd /home/ispamr/portofolio

# Copy your photo from Windows to WSL (adjust the path to match your file location)
cp "/mnt/c/Users/OsamaHussien/Downloads/temp_image_20240902_145025_918f4042-a61e-4b02-96dc-45e9348f36e7 (1).jpg" profile.jpg

# Commit and push
git add profile.jpg
git commit -m "Update profile photo"
git push origin main
```

### Alternative Method (Via GitHub):

1. Go to https://github.com/iSpammer/portfolio
2. Click on `profile.jpg`
3. Click the trash icon to delete it
4. Click "Add file" → "Upload files"
5. Upload your actual photo renamed as `profile.jpg`
6. Commit the changes

## Image Recommendations

- **Size**: At least 400x400 pixels (for retina displays)
- **Format**: JPG or PNG
- **File size**: Under 500KB for fast loading
- **Aspect ratio**: Square (1:1) works best
- **Background**: Professional background or solid color

## Current Badge Images Included

✅ **Successfully Added:**
- AWS Solutions Architect Associate
- AWS Cloud Practitioner
- ISC2 Certified in Cybersecurity
- Cisco Networking Basics
- Cisco Introduction to Cybersecurity
- IBM Agile Explorer

🎨 **Using Icon Placeholders:**
- SAP badges (3 badges)
- AWS Cloud Quest badges (2 badges)
- IBM badges (remaining 3 badges)
- Pearson Intern badge
- Other Cisco badge

The badges with icons still look professional but show gradient backgrounds with FontAwesome icons instead of the actual badge images.

## What's Live Now

Your website at **https://osstech.uk** now includes:
- ✅ 6 actual Credly badge images
- ✅ Profile image placeholder (your initials)
- ✅ All 16 badges listed with proper information
- ✅ Direct link to your Credly profile

Clear your browser cache (Ctrl+F5) to see the updates!
