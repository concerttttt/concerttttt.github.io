# Images Directory

This directory should contain your images and videos for your website, including:

1. **Profile picture**: Name it `YourPhoto.jpg` or update the reference in index.html
2. **Project images**: For each project, consider having:
   - A static "before" image: `project_name_before.jpg` 
   - An "after" image or video: `project_name_after.jpg` or `project_name.mp4`

## Image Hover Effect

The template includes a hover effect where hovering over a project image shows a second image or plays a video. For this to work:

1. Each project has two images in a div with classes "one" and "two"
2. The JavaScript toggle functions change the opacity based on mouse events
3. Make sure your image dimensions are consistent (160x160px works well for thumbnails)

## Example Image Organization

```
images/
├── YourPhoto.jpg           # Your profile/headshot
├── project1_before.jpg     # Static image shown by default
├── project1_after.jpg      # Image shown on hover
├── project2_before.jpg     
├── project2.mp4            # Video played on hover
└── favicon/
    └── favicon.ico         # Website favicon
```

Replace these placeholder images with your own content. 