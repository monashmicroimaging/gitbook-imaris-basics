# PART 2: GETTING STARTED IN IMARIS {#part-2-getting-started-in-imaris}

## Converting your images to the Imaris file format {#opening-images}

We recommend using the Imaris File Converter tool to convert your images into the Imaris .ims file format. This allows quicker loading and visualization of very large images.

The Imaris File Converter cam be downloaded from the Bitplane website at: http://www.bitplane.com/download It is free and has no license restrictions, so you can run it at home, and on as many computers as you'd like.

> For this purpose it stores not only the original image data but also lower resolution versions of the original data. This allows the visualization software to load only low resolution data when those are sufficient. Also for the purpose of fast visualization the Imaris File Format stores the image data in contiguous 3D chunks \(hdf-terminology for 3D blocks\) which allows the visualization software to load only those data that are in the field of view. The multiresolution structure and the chunk-wise storage layout are the cornerstones of this high performance file format.

You do not have to convert your images before viewing them in Imaris, although we do recommend it. Imaris can read and open many different image formats, including standard formats such as .tif and .jpg as well as bio-formats from microscope/image capture software. 

## Opening Images {#opening-images}

When using Imaris in Surpass mode you can open images by ‘dragging and dropping’ them into the Imaris window, or by going to **File -&gt; Open** and selecting your file from the explorer window.

To add files to Imaris in Arena mode see the section on Arena below.

Imaris will automatically read the dimensions \(channels, time, z-stacks\) and display them appropriately in the software.

## The Main Imaris Interface {#the-main-imaris-interface}

Imaris opens as a full window on your screen. In the main \(Surpass\) window there are a number of icon panels for different functions. These are outlined below.

![](/assets/part_1/imaris-main-interface.jpg)

## Rearranging Image Dimensions {#rearranging-image-dimensions}

On rare occasions Imaris will read the dimensions of your image in the wrong order and display them incorrectly, for example displaying time points as 3D z-series or different channels as time points.

You can easily correct this by going to the **Image Processing** menu and selecting the dimensions you wish to swap; either **Swap Time and Z** or **Swap Time and Channels**.

![](/assets/part_2/rearrange-image-dimensions.jpg)

## Imaris Modes {#imaris-modes}

There are 3 different ways to view your data in Imaris, which we will refer to here as “Operating modes”. These are Arena Mode, Surpass Viewing Mode and Vantage. You can switch between these modes by selecting the corresponding icon from the top left panel of the main Imaris window.

![](/assets/part_2/modes_arena_surpass_vantage.jpg)

When you first open Imaris v8 it will start in **Arena Mode**. In the Arena you can pre-load all of the images you want to examine, and sort them into different experiments and groups. Arena is not present in earlier version of Imaris.

In **Surpass Viewing Mode** you can visualise the selected images in 2D, 3D or 4D \(time series only\), navigate around the image and carry out quantification.

In **Vantage** you can generate graphs and plots from your image data. This is rarely used, as most people export quantification data to other statistics programs such as Excel, SPSS or GraphPad Prism. As such the use of Vantage is not covered in the Imaris Basics workshop.

## Using the Imaris Arena {#using-the-imaris-arena}

To use Arena, select your workspace or create a new one by clicking the **New Assay** icon.

![](/assets/part_2/create_new_assay.jpg)

Give the “assay” or experiment folder a name and click **OK**.

![](/assets/part_2/create_new_assay_name.jpg)

This will generate a new section in the Arena workspace where you can add images and groups.

![](/assets/part_2/new_assay_workspace.jpg)

You can now add images by dragging and dropping into the Arena workspace or clicking the **new Image** icon and selecting your file from the explorer window.

![](/assets/part_2/add_new_images.jpg)

You can group your images together \(ie: control vs treatment or by experiment date\) by creating a new group within the workspace. Click on the **New Group** icon, name the group and click **OK.**

![](/assets/part_2/create_new_group.jpg)

![](/assets/part_2/create_new_group_name.jpg)

Drag and drop your images into the group icon in the workspace to move them.

To delete an image, group or assay from Arena select the image or icon and click the **Delete** button in the panel.

To open a specific image from Arena in the Surpass Viewing Mode, double click the image.

## Options in Surpass Viewing Mode {#options-in-surpass-viewing-mode}

In **Surpass Viewing Mode** your data will open as a single image in 2D, 3D or 4D, depending on the data type. This is called the **3D View**.

![](/assets/part_2/3d_view_surpass_mode.jpg)

You can choose to work in this 3D View mode or you can select options from the **Slice/Easy 3D** icon. You can switch between the two easily using the respective icons in the top panel.

From the Slice/Easy 3D Menu you can select several different viewing options from the drop down menu, accessible by clicking on the small down arrow.

![](/assets/part_2/3d_view_options.jpg)

**Slice** will show each z-section of the 3D image as a single panel and allows you to scroll through the section using the slider on the left hand side of the window.

![](/assets/part_2/3d_view_slice.jpg)

Another popular option is the **Gallery View**. This shows all slices from a 3D image in order in a gallery panel.

![](/assets/part_2/3d_view_gallery_panel.jpg)

