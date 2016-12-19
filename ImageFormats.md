## Types of image files
There are several types of image files you'll run into as you work with the images you've captured on your camera. JPG, PNG, TIFF, RAW - what's the difference between these types of files and does it matter which ones I use? It absolutely does! Much of it comes down to file size and lossiness. 

When you take a photo with your DSLR, the camera has to store all the data about that photo into a file that can be read by your computer. Color information is stored about each pixel so that an accurate image can be recreated when you view it. 

Because it takes a LOT of data to store information about every pixel, algorithms have been developed to "compress" the files by looking for patterns within the photo. More lossy algorithms not only look for patterns but "toss out" information deemed to be "unnecessary". This usually doesn't matter to the naked eye but prevents you from doing certain types of edits in Lightroom because valuable information is "lost".

Let's take a look at the various file types:

**TIFF** is a very flexible format that is mostly lossless. It is used almost exclusively as a lossless image storage format that uses no compression at all. Most graphics programs that use TIFF do not need compression. Consequently, file sizes are quite big. 

**PNG** is also a lossless storage format. However, in contrast with common TIFF usage, it looks for patterns in the image that it can use to compress file size. The compression is exactly reversible, so the image is recovered exactly.

**JPG** is optimized for photographs and similar continuous tone images that contain many, many colors. It can achieve astounding compression ratios even while maintaining very high image quality. JPG works by analyzing images and discarding kinds of information that the eye is least likely to notice. It stores information as 24 bit color. Important: the degree of compression of JPG is adjustable. At moderate compression levels of photographic images, it is very difficult for the eye to discern any difference from the original, even at extreme magnification. Compression factors of more than 20 are often quite acceptable. Better graphics programs, such as Photoshop, allow you to view the image quality and file size as a function of compression level, so that you can conveniently choose the balance between quality and file size. **Importantly, each edit you do to a JPG will further degrade the overall quality of the image.**

**RAW** is an image output option available on most DSLR cameras. Though lossless, it is a factor of three of four times smaller than TIFF files of the same image. The disadvantage is that there is a different RAW format for each manufacturer, and so you may have to use the manufacturer's software to view the images. **DNG** is a universal RAW format developed by Adobe and **NEF** is Nikon's proprietary format.

## TL;DR on image types
**RAW** is the most lossless format, preserving a ton of information about the photo including hue, white balance, tone, etc. It is the best file type to use as the "master" image you capture.

**TIFF** is a lossless format. When you choose to edit a RAW file in Photoshop from Lightroom, it will convert to this format and your edits will be saved in this format.

**PNG** is the next best option after TIFF and RAW because it is mostly lossless as well. It looks for patterns of pixels to save space. It does however lose information about hue, white balance and tone.

**JPG** is very lossy because it tosses out information it thinks the human eye won't need. It is great for photos you want to put on a blog, print at your local photo printer and for one time use. You really don't want to be editing it though as each edit degrades the quality.
