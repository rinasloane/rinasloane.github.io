This folder should contain your cover image named `cover.jpg`.

Steps to add the image using GitHub web UI:
1. Click "Add file" → "Upload files" in this repo.
2. Upload your image and set the path to `assets/cover.jpg`.

If you prefer, you can upload from the command line:

  mkdir -p assets
  cp /path/to/your/image.jpg assets/cover.jpg
  git add assets/cover.jpg
  git commit -m "Add cover image"
  git push
