# Collection Objects 

In general your exhibit can contain three types of objects:

- files in the "objects" folder  -- .jpg, .pdf, or .mp3 files added to the repository and referenced in the "filename" field.
- YouTube and Vimeo videos -- IDs referencing the videos added to the metadata in "youtubeid" or "vimeoid" columns.
- external object links -- direct URLs to web accessible files (images, pdfs, mp3s, videos) referenced in the "filename" field.

Student instructions are described in the [Digitization Guidelines](https://learn-static.github.io/digital-exhibit-lab/project/digitization.html) ("pages/project/digitization.md") and [Curation Guidelines](https://learn-static.github.io/digital-exhibit-lab/project/curation.html) ("pages/project/curation.md").

## Objects Folder

This option is mostly likely to be used if your project involves digitization. 
You will need a workflow for the students to add their files to the "objects" folder. 

If students have GitHub accounts and access to the repository, they can upload them directly using the GitHub web interface.
If your project does not have the students directly working in GitHub, it may be easiest to have the instructor or digitization lab coordinate uploading the objects instead.

Tips:

- Have a clear file naming convention. Getting file names correct in the metadata "filename" field (with correct case) is essential for the exhibit to work. 
- The exhibit does not use thumbnails for images, so the images should be a reasonable size for display on the web--this isn't designed for max rez digitization!
- GitHub repositories are not designed for large binary files, so don't make your collection too big!
- We have had students add their digitized objects to a shared Google Drive folder, allowing the instructors to check over the files and upload as a batch to the project.

## YouTube and Vimeo videos

YouTube and Vimeo videos are a special type of external item in the template. 

To include videos add a "youtubeid" and/or "vimeoid" column to the metadata template. 
For video items, leave the "filename" field blank, and fill in the corresponding "youtubeid" / "vimeoid".
The template will display thumbnails and the video on the item page.

For non-video items, always leave "youtubeid" / "vimeoid" blank.

## External Objects

Using links to external files in the "filename" field enables you to add objects without needing to add any files to your project. 
This is a great option for curating a collection of items from across multiple collections and sources.

We used this option to introduce students to our digital collections and how they can find download links to our objects. 
Exploring digital collections and learning how to right-click to find image links builds important digital literacy skills.
Curating items from existing collections could be done to supplement digitized items or as the primary aim of the project.

### Potential Sources for Curation

To find good digital collections to use for curation projects, look for organizations who make efforts to openly license and distribute their items. 
Public domain or CC0 collections are good options. 
Some organizations and digital repository platforms make it easy to find an image/pdf file link, others might require some investigation to figure out the pattern.

Many platforms now provide images following the [IIIF standard](https://iiif.io/) which provides a recipe for URLs to get images.
For a more advanced class you could introduce the idea of APIs and how IIIF works, having students learn how to construct the link following the recipes.
Since they follow the IIIF standard, the API patterns are the same on any site, once you figure out the correct server URL and item ID.

Here are some example options:

#### Farm Security Administration/Office of War Information Black-and-White Negatives

- Students explore the LOC [Farm Security Administration/Office of War Information Black-and-White Negatives](https://www.loc.gov/collections/fsa-owi-black-and-white-negatives/)
- Find an item of interest, e.g. https://www.loc.gov/item/2017826254/
- Below the image preview, look for the "Download" option. Select the largest JPEG option, click go. 
- This should open the image in a new tab. Copy the link from that tab into metadata "filename" field.
- Alternatively, right click on the preview image, select "copy image address"--this will provide an image appropriately sized for our exhibit.
- IIIF is also available.

#### Chronicling America

- Students explore the LOC [Chronicling America newspapers collection](https://chroniclingamerica.loc.gov/)
- Find an item of interest, e.g. https://chroniclingamerica.loc.gov/lccn/sn88078386/1922-05-05/ed-1/seq-1/
- On the item page, look above the page image for download links. 
- Copy the "PDF" link and paste into metadata "filename" field.

#### Smithsonian Open Access

- Students explore the [Smithsonian Open Access portal](https://www.si.edu/openaccess) (or do a search with option "Media useage: Open Access Media (CC0)")
- Find item of interest, e.g. https://www.si.edu/object/shoshone-falls-snake-river-idaho-view-across-top-falls:saam_1994.91.141
- Right click on the item image, select "copy image address", and paste the link into the metadata "filename" field. (don't use the download button, since this preps the file differently and will not work)
- IIIF is also available--click the IIIF icon, click "manifest". In the JSON you will eventually find a value in sequences > canvases > images > resource > id, that looks like a link to a .jpg file, e.g. https://ids.si.edu/ids/iiif/SAAM-1994.91.141_2/full/full/0/default.jpg
