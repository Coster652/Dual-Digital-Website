IMAGES EXPLANATION

After a thorough search of the original website project (/home/ubuntu/dual_digital_network_website) and the static site directory (/home/ubuntu/Word Press Ready/static-site/), I found that there are no local image files in either location.

The website is built using Next.js and is using external image URLs for all its images. Here are some of the external image URLs used in the website:

1. Hero image: https://i.pinimg.com/originals/2f/0a/f1/2f0af1c5bcc25af712cfc1c74df20293.jpg

2. Blog images:
   - https://images.pexels.com/photos/374016/pexels-photo-374016.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260
   - https://img.freepik.com/free-photo/side-view-real-estate-agent-holding-tablet_23-2150225243.jpg
   - https://as1.ftcdn.net/v2/jpg/04/49/75/24/1000_F_449752429_cBk7nGIq2lf9DGOZepoeNpDE4ZEmoqYt.jpg
   - https://i0.wp.com/theecmconsultant.com/wp-content/uploads/2022/04/business-process-automation-tools.jpg?fit=1920%2C1280&ssl=1

3. Contact form image: "/Screenshot 2025-05-24 at 9.39.01 PM.png" (This appears to be a reference to a local file, but the file itself is not present in the project directory)

This explains why the images folder in the static site directory is empty - there were no local image files to copy over from the original project.

To use images in the WordPress site, you would need to:
1. Download the images from the external URLs mentioned above
2. Upload them to your WordPress media library
3. Update the image references in your WordPress content to point to the uploaded images
