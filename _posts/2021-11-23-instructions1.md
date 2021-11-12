---
title: "Use WinStitch to Convert an Image into a Cross-Stitch Pattern"
date: 2021-11-23 21:41:00 -0500
categories: [PORTFOLIO, INSTRUCTIONS]
tags: [instructions, tutorial, user-facing documentation]
---
Many cross-stitchers who are familiar with modern trends in cross-stitching also know about full coverage patterns. Some cross-stitchers want to make full-coverage patterns from artwork or photography but don’t know how or don’t have the time. Computer programs such as WinStitch can convert photographs and artwork into these patterns, but the results can look subpar at times. Using basic skills in Photoshop and WinStitch, you can prepare and make professional-looking patterns!

## Prerequisites

You will need the following:

| Prerequisite | Description |
| ----------- | ----------- |
| *Computer, mouse, and keyboard* | Must meet the minimum hardware requirements for WinStitch and Photoshop. |
| *WinStitch* | Install and use the latest version. |
| *Adobe Photoshop* | Install and use the latest version. Previous versions of Photoshop, such as Adobe Photoshop CS6, may be used instead if they have the Adjustment Layers function.|
| *An image file* | Use artwork or photography that you have created, or have permission to use, especially if you are making the pattern for commercial purposes. |

*Note:* Other image editing software, such as Paint.NET or GIMP, can be used instead of Photoshop, as they have similar capabilities, but instructions for using those programs are beyond the purview of this document.

## Image Preparation in Photoshop

WinStitch’s conversion feature works well with a variety of mediums. However, it typically works best with an image file that has a limited color range due to the limited number of colors available in embroidery floss. The following procedure in Photoshop ensures a picture is prepared for conversion.

### Resizing Your Image

Before you can begin reducing colors, you need to reduce or enlarge your image to the final size of the pattern.

1. Make or find an image file (such as scanned artwork, a digital painting, or a photo) you want to convert into a pattern. The example image used for this guide is Edmund Leighton’s 1901 painting, *The Accolade*, a public-domain painting sourced from [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Accolade_by_Edmund_Blair_Leighton.jpg).
2. Open Photoshop.
3. Using the menu, click **Open...**, then navigate to your image file in the explorer window.
4. Select **Open** in the dialog box to open your image file.
5. Using the menu, click Image > Image Size. Doing so brings up the Image Size dialog box, where you can adjust the size of the image (see Figure 1).

<figure style="text-align:center;">
        <img src="/assets/img/instructions1-f1.png">
        <figcaption><b>Figure 1.</b> The Image Size dialog box, demonstrating the unit drop-down menu.</figcaption>
</figure>

6. Click the unit of measure next to Width or Height, which is likely set either to Pixels or Inches, to open the drop-down menu. Set the unit of measure to Inches.
7. Adjust the picture to your desired size by typing your values into the Width and Height fields.

    *Note:* Larger pictures result in larger canvases with plenty of room for details, so make sure your image file is bigger than about 15 inches wide and tall if you want WinStitch’s conversion to preserve as much detail as possible from the original file.
8. Click **OK**.

### Posterizing the Image

Now that the picture is the desired size, we must limit the color palette. One of the easiest ways to do this in Photoshop is to use a Posterize adjustment layer:

1. Using the menu, select **Layer** > **New Adjustment Layer** > **Posterize**. Click **OK** on the New Layer dialog box. Doing so will bring up a new window in the right-hand pane of Photoshop above the Layers window called Properties (see Figure 2).

    <figure style="text-align:center;">
        <img src="/assets/img/instructions1-f2.png">
        <figcaption><b>Figure 2.</b> The Properties window associated with the Posterize adjustment layer.</figcaption>
    </figure>

2. Type a value in the field by Levels. The lower the value, the fewer colors the image has. Choose a value that gives you the best-looking picture.

    *Note:* The image will show your changes in real time, allowing you to adjust the image freely. Start at `2` and go up from there until you are satisfied.
3. From the menu, select **File** > **Save As**, then name the file a name you can find later.
4. Select **PNG** from the drop-down menu, then click **Save**.

## Conversion in WinStitch

Now that the image is ready, we can move on to using WinStitch.

## Importing the File

WinStitch has an automatic image import wizard, but we can get better results using the Advanced Image Import tool.

1. Open WinStitch. Select the **Convert Image** button in the left-hand menu.
2. Select **Advanced Image Import.** Navigate to your prepared image file in the explorer window, then click the **Open** button.
   The Import a Picture dialog box will appear (see Figure 3). Chart Width determines the width of the pattern, and the value of Stitches/in determines the pattern’s fabric count. Underneath the sliding arrows next to Chart Width are a set of values; this is the size of the pattern WinStitch has automatically suggested.

    <figure style="text-align:center;">
        <img src="/assets/img/instructions1-f3.png">
        <figcaption><b>Figure 3.</b> The Import a Picture dialog box.</figcaption>
    </figure>

3. Select the **small arrows** next to Stitches/in and set the fabric count to your desired fabric count.

    *Note:* The higher the fabric count, the more detail WinStitch will preserve in the conversion process. Most full-coverage patterns from designers like Heaven and Earth Designs use 24ct fabric.
4. Select the **box** in the middle of the arrows next to Chart Width and slide it left or right until the values beneath the image correspond to the actual size of your image as you made it in Photoshop. The example image was resized to 15 inches wide and 25 inches tall in Photoshop, so set it to the same size in WinStitch.
5. Select **DMC.threads** from the drop-down menu at the bottom of the dialog box.
6. Click **OK**. Doing so will bring up a new WinStitch pattern creation window showing your imported pattern (see Figure 4).

    <figure style="text-align:center;">
        <img src="/assets/img/instructions1-f4.png">
        <figcaption><b>Figure 4.</b> The pattern creation window.</figcaption>
    </figure>

### Finalizing the Pattern

Once the new window is displayed, it’s time to review the pattern and export it for printing.

1. Select the **Grid** button in the second toolbar from the top of the window.
2. Select **Grid Visible**. This will turn the gridlines off and allow you to see your created pattern.
3. Click the **Zoom** button (represented by a magnifying glass icon) in the bottom-right corner, then click any value you wish to preview your pattern.
4. Once you are satisfied with the pattern, select **Import/Export** from the menu.
5. Select **Export to PDF for Pattern Keeper**. Click OK on the dialog box, then name your new pattern chart.

## Troubleshooting

The conversion process outlined here isn’t always perfect. Here are some suggestions for common issues:

* Are there lots of pure black dots in not-so-dark shaded areas? Is the image too washed out? Use a Brightness/Contrast adjustment layer in Photoshop to increase the brightness of the image a little or adjust the contrast.

* Does the pattern look too pixelated? Either increase the levels in the Posterize adjustment layer in Photoshop or skip that step entirely.

* Are the colors on the screen too bright or too dull? Use a Hue/Saturation adjustment layer in Photoshop to correct the saturation levels.
