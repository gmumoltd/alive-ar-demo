ALIVE - AR art demo
===================

What's in this folder
  index.html      the AR viewer (open this on your phone)
  display.html    shows the artwork + a QR code (open this on a laptop)
  assets/artwork.jpg   the sample artwork (the image the phone recognises)
  assets/video.mp4     the video that plays on top of it

Put it online (free, about 2 minutes)
  1. Go to https://app.netlify.com/drop
  2. Drag this whole folder onto the page.
  3. Netlify gives you a link like https://something.netlify.app
     (make a free account so the link doesn't expire)

Try it
  1. On a laptop, open  <your link>/display.html
  2. Scan the QR code with your phone.
  3. Tap "Start camera", allow the camera, and point at the artwork.

Swap in your own artwork
  Replace assets/artwork.jpg and assets/video.mp4 with your own files
  (keep the same names), then drag the folder onto Netlify again.
  Tips: use a detailed, high-contrast image, and a short MP4 video
  (under 10 MB) with the same shape as the image.

Why it needs to be online
  Phones only allow camera access on secure (https) websites, so it
  won't work if you just open index.html from your files.
