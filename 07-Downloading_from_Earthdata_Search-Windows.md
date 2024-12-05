> *This tutorial will show you how to download ECOSTRESS data from
> Earthdata Search on Windows.*

# Table of Contents

[What is Earthdata Search?](#what-is-earthdata-search)

[Requesting files from Earthdata Search](#requesting-files-from-earthdata-search)

[Installing Earthdata Download](#installing-earthdata-download)

[Downloading the files to your Computer](#downloading-the-files-to-your-computer)

# What is Earthdata Search?

Earthdata Search is a customized search experience that allows users to
filter and discover data. It allows for easy access and use of NASA’s
Earth Observing System Data and Information System (EOSDIS). There is a
variety of data available, including ECOSTRESS data.

## Requesting files from Earthdata Search

1.  Start by going to <https://search.earthdata.nasa.gov/search> or by
    searching for **Earthdata Search** on the Web. In the top right,
    select **Earthdata Login**. This will take you to the Earthdata
    Login page.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image1.png"
style="width:4.12462in;height:2.30556in"
alt="Graphical user interface, application, website Description automatically generated" />

2.  Type in your username and password and select **Login**. This will
    redirect you back to the **Earthdata Search** page.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image2.png"
style="width:5.35068in;height:2.46897in"
alt="Graphical user interface, text, application, website Description automatically generated" />

3.  The left most panel of the Earthdata Search window is where you can
    search for data. The preferences that you set in the left panel will
    change what results are shown in the middle panel. Let’s look at
    some of the ways we can do this. First, at the very top there is a
    search bar that says **Search for collections or topics**. This
    allows you to search for different products or key words if you know
    exactly what you are looking for. Select the eraser icon to clear
    your search.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image3.png"
style="width:3.85417in;height:0.71096in"
alt="Graphical user interface Description automatically generated with low confidence" />

4.  Below that we have three filtering options available. The first
    **Calendar** icon allows you to set start and end dates to filter
    your search. This is called a **Temporal** filter. To confirm, click
    **Apply**.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image4.png"
style="width:3.97222in;height:2.2118in"
alt="Graphical user interface, text, application Description automatically generated" />

5.  Next, the icon that looks like a crop symbol allows you to set a
    **Spatial** filter around your area of interest. If you click on it,
    a dropdown will appear with different options.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image5.png"
style="width:1.93056in;height:1.99152in"
alt="Graphical user interface, application Description automatically generated" />

1.  You can select **polygon** to draw a shape with points on the map.
    To finish the polygon, either **double click** or **click on the
    first point**.

2.  You can select a predefined shape (**Rectangle** or **Circle**) or
    **Point** and place it on the map.

3.  Or, you can upload a shapefile by selecting **File**. This will open
    a pop-up that will allow you to **Browse Files** on your computer.
    Make sure the file is in one of the valid formats listed.
    Alternatively, you can drag and drop shapefiles directly onto the
    map.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image6.png"
style="width:3.49005in;height:2.84722in"
alt="Graphical user interface, text, application, email Description automatically generated" />

6.  The last icon is the **advanced search icon** this allows you to
    search for Hydrological Units (HUC ID), if that is something you are
    interested in.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image7.png"
style="width:0.82in;height:1in"
alt="Graphical user interface, application Description automatically generated" />
<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image8.png"
style="width:3.66667in;height:1.83333in"
alt="Graphical user interface, application Description automatically generated" />

7.  To practice searching for ECOSTRESS data, let’s do a practice
    example. For this example, leave the temporal filter and advanced
    search blank. For the **Spatial** filter, zoom into southern
    California and find the **Salton Sea**. Use the **Rectangle** option
    under the Spatial filter to draw a box around the Salton Sea.

> <img
> src="07-Downloading_from_Earthdata_Search_images-Windows /media/image9.png"
> style="width:5.97222in;height:2.55734in"
> alt="Graphical user interface, application Description automatically generated" />

8.  Now let’s look at the **Filter Collections** box. This box allows
    you to select preferences for your search based of criteria in
    different categories including **Keywords**, **Projects**, **Data
    Format**, and so much more. If you are interested in using a variety
    of NASA’s Earthdata, I encourage you to explore and see your
    different options!

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image10.png"
style="width:1.65734in;height:3.20301in"
alt="Graphical user interface, application Description automatically generated" />

9.  To find ECOSTRESS data, click the dropdown next to the **Projects**
    category in the **Filter Collections** box. In the list of options,
    scroll down to **ECOSTRESS** and click the box next to it to make a
    checkmark appear. You will now see that next to **Projects** it says
    **1 Selected** and the middle panel now shows **ECOSTRESS**
    products.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image11.png"
style="width:1.65328in;height:2.79876in"
alt="Table Description automatically generated with medium confidence" />

10. You can also filter the ECOSTRESS products by data type. To do this,
    click the dropdown next to **Data Format** and select the box next
    to the data type you prefer. In this case, let’s select **Cloud
    Optimized GeoTIFF (COG)**.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image12.png"
style="width:2.30556in;height:0.82666in"
alt="Graphical user interface, text, application, chat or text message Description automatically generated" />

11. Now in the center panel, you will see a list of all ECOSTRESS
    collections with a GeoTIFF data type. You can scroll through the
    options to see what is available in the area you selected. If you
    hover your mouse over the collection, more options will appear.
    Select the **i information** icon to learn more about the
    collection. You can also select the **green plus** to add the entire
    collection to your project to later download.

> <img
> src="07-Downloading_from_Earthdata_Search_images-Windows /media/image13.png"
> style="width:6.01987in;height:2.4255in"
> alt="Graphical user interface, application Description automatically generated" />

12. For now, let’s just click on the name of the first collection
    listed. It should be **ECOSTRESS Tiled Land Surface Temperature and
    Emissivity Instantaneous L2 Global 70 m V002**.

> <img
> src="07-Downloading_from_Earthdata_Search_images-Windows /media/image14.png"
> style="width:6.18013in;height:1.84149in"
> alt="Graphical user interface, text, application, email Description automatically generated" />

13. Once you click on the collection, the middle panel will now display
    the **granules** available in that collection that align with your
    search parameters. You will also see a **timeline** at the bottom of
    the screen. The **green bars** on the timeline represent the dates
    when ECOSTRESS data with the specifications you provided is
    available. This timeline is interactive and can be used instead of
    setting a temporal resolution with the calendar icon I showed
    before.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image15.png"
style="width:6.5in;height:3.17431in"
alt="Graphical user interface, website Description automatically generated" />

14. To set a temporal filter using the timeline, start by adjusting the
    units. Click the up or down arrows to change the units from **Day**,
    to **Month**, to **Year**. For now, I will set mine to **Year**.

> <img
> src="07-Downloading_from_Earthdata_Search_images-Windows /media/image16.png"
> style="width:1.09722in;height:0.93056in"
> alt="Graphical user interface, application Description automatically generated" />

15. Next, hold your mouse in the dark gray section above the timeline
    and **drag** across the times you want to filter. Once you let go, a
    **red filter** will be placed over the times you selected. If you
    want to adjust the filter, click and drag the **end lines** of the
    filter to a new position. For now, I want to filter for data from
    the year **2023**.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image17.png"
style="width:6.60727in;height:0.58943in" />

16. Now let’s investigate the granules available. If it is helpful to
    you, you can sort them based on **start date** or **end date** being
    the **oldest** or **newest** by selecting an option under the
    **Sort** dropdown.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image18.png"
style="width:4.10416in;height:1.37323in"
alt="Graphical user interface, text, application, chat or text message Description automatically generated" />

17. Also, if you hover over the **View** icon that looks like bullet
    points, you can choose to view the granules as a **list** or a
    **table**.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image19.png"
style="width:4.18832in;height:1.27748in"
alt="Graphical user interface, text, application, chat or text message Description automatically generated" />

18. Next, **hover your mouse** over one of the granules listed. Notice
    that a **green box** appears around the granule’s description. Also,
    the location of the granule is **highlighted on the map**.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image20.png"
style="width:6.41743in;height:2.75621in"
alt="Graphical user interface, website Description automatically generated" />

19. In the box with the granule description, there are a few more ways
    you can interact with it. You can select the **green plus** sign to
    **add it to a project** to be downloaded later.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image21.png"
style="width:2.44444in;height:2.0546in"
alt="Graphical user interface, application Description automatically generated" />

1.  You can also select the **download** button to instantly download
    just that granule. This is especially helpful if you just want one
    file to run tests with.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image22.png"
style="width:2.51994in;height:2.11806in"
alt="Application Description automatically generated with low confidence" />

2.  Also, if you click the **three dots** menu, you can either select
    **View details** which will give you more information and metadata
    on the granule, or you can select **Filter granule** to hide that
    specific file from your search.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image23.png"
style="width:2.59663in;height:2.13971in"
alt="Graphical user interface, text, application, chat or text message Description automatically generated" />

20. For the sake of our practice example, let’s download a few granules.
    I am going to select the **green plus sign** next to the seven
    granules I found for my area taken on December 14<sup>th</sup>, 2023
    (**2023-12-14**). You will notice a few things on your screen
    change. First, the green plus signs become **red minus signs** which
    you can click if you want to remove them from the selection. Also,
    the green **Download** button now displays the number of granules
    selected **(7)**. Finally, at the top right of the screen you should
    see a new tab titled **My Project**. To continue, click on either
    the green **Download** button or the **My Project** tab. Both of
    these options will take you to the download window.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image24.png"
style="width:5.72429in;height:2.45851in"
alt="Graphical user interface, application Description automatically generated" />

21. In the download window you will have the option to name your project
    by clicking the pen and paper icon next to **Untitled Project**.
    This is helpful if you ever want to revisit this download or share
    it with others. I am going to call this search
    **Salton_Sea_ECOSTRESS**.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image25.png"
style="width:2.28812in;height:0.55932in"
alt="Text Description automatically generated with medium confidence" />

1.  Now when you select your **profile** in the top right and go to
    **Saved Projects** you will see the **Salton_Sea_ECOSTRESS**
    project.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image26.png"
style="width:1.74557in;height:1.69126in"
alt="Graphical user interface, text, application Description automatically generated" />

22. The center pane of the download window is where you set **Edit
    Options**. Depending on the product you are downloading, there may
    be more options available. For this example, we will just keep the
    default options. Now press **Download Data** to start downloading.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image27.png"
style="width:5.21365in;height:1.97796in"
alt="Graphical user interface, application, Teams Description automatically generated" />

23. Finally, this will take you to a **Download Status** page where you
    can track your orders being processed.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image28.png"
style="width:5.88889in;height:1.25966in" />

## Installing Earthdata Download

1.  There are a few ways to actually download the files to your
    computer. If you have a preferred way to do this, you can go ahead
    with that method. However, this tutorial will show you how to
    install **Earthdata Download** in order to download the files. To
    start, scroll down and **click** the **Download Files** button.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image29.png"
style="width:6.48611in;height:2.125in" />

2.  In the pop up, look for the link under **Don’t have Earthdata
    Download Installed?** and click on where it says **Downloads Page**.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image30.png"
style="width:3.3849in;height:2.875in" />

3.  On the new website, click the **Download for Windows** button.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image31.png"
style="width:3.44434in;height:2.05556in" />

4.  Go to your **downloads folder** and **double click** on the
    installer to launch it.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image32.png"
style="width:3.63171in;height:2.29167in" />

5.  You might get a pop-up saying **Windows protected your PC**. If this
    happens, press **More info**.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image33.png"
style="width:4.07639in;height:3.82352in" />

6.  Then select **Run Anyway**.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image34.png"
style="width:4.06944in;height:3.82571in" />

7.  In the new set-up window, press **Next**.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image35.png"
style="width:3.1875in;height:2.47917in" />

8.  Then, press **Install**.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image36.png"
style="width:3.19444in;height:2.49481in" />

9.  Once it has finished installing, press **Finish** to close the
    installer.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image37.png"
style="width:3.20833in;height:2.49118in" />

## Downloading the files to your Computer

1.  Now that we have **Earthdata Download** installed, lets open it. To
    do this, search for **Earthdata Download** in the **Windows search
    bar** and press **Enter** to open it.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image38.png"
style="width:3.79861in;height:3.29538in" />

2.  Once you have the **Earthdata Download** application open, go back
    to your Earthdata request **Download Status** page and select the
    **Download Files** button.

> <img
> src="07-Downloading_from_Earthdata_Search_images-Windows /media/image29.png"
> style="width:5.87141in;height:1.92361in"
> alt="Graphical user interface, application, Teams Description automatically generated" />

3.  A pop-up may appear asking you if you would like to open Earthdata
    Download. Click **Open Earthdata Download**.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image39.png"
style="width:2.7383in;height:1.375in" />

4.  A new pop-up will appear in the **Earthdata Download** application.
    It will ask you to set a **location** on your computer for the
    downloaded files to go. By default, this is listed as your
    **downloads folder**, however if you would like to change it, you
    can do so now. Also, there is a **check box** allowing you to decide
    if you want to be asked this question again. Once you have made your
    decisions, press the **Begin download** button.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image40.png"
style="width:4.54907in;height:3.41667in" />

5.  Next, a window will pop-up asking you to login to **Earthdata
    Search**. Enter your credentials and press **Log In**.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image41.png"
style="width:4.57639in;height:2.85841in" />

6.  You may get another pop-up asking to again **open Earthdata
    Download**. Click **Open**.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image42.png"
style="width:3.57194in;height:1.63889in" />

7.  Go back to the **Earthdata Download application**. You should see a
    **progress bar** showing how much of the data has been downloaded.
    Let it finish downloading.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image43.png"
style="width:5.1576in;height:3.88889in" />

**Tip**: If your download time keeps passing, but there is **no progress
in the number of files** being downloaded, there are a few things you
can do to fix this. First, try **pausing** and **resuming** the
download.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image440.png"
style="width:0.72455in;height:0.30897in"
alt="A picture containing graphical user interface Description automatically generated" />
<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image450.png"
style="width:0.85417in;height:0.30422in" />

If there is still no progress being made, **click on the download**.<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image460.png"
style="width:4.38194in;height:0.59229in" />

In the new screen, all the files will be listed with their status. Click
the checkbox to **Hide Complete** files.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image470.png"
style="width:1.05808in;height:0.26452in"
alt="A picture containing text Description automatically generated" />

Then, find the file or files that are stuck and not downloading. They
should say **Not yet started**. Hover over the file name, click on the
**three** **dots**, and select **Restart File**. This should cause it to
start downloading.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image480.png"
style="width:4.36806in;height:0.78465in" />

Furthermore, if you get a warning that looks like this, just press
**Retry** and it should resolve.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image490.png"
style="width:3.44444in;height:0.57933in" />

8.  You will know it is done downloading the files when it says
    **complete**.

<img
src="07-Downloading_from_Earthdata_Search_images-Windows /media/image50.png"
style="width:5.44444in;height:0.89673in" />

You now have ECOSTRESS files downloaded to your computer!

**Tip**: You can look at the [ECOSTRESS Naming
Conventions](https://lpdaac.usgs.gov/data/get-started-data/collection-overview/missions/ecostress-overview/#ecostress-naming-conventions)
to help make sense of the files you downloaded!
