# digital-exhibit-lab Overview for Instructors

Digital Exhibit Lab is a Learn-Static template for creating an assignment that gives students hands-on experience creating a digital collection. 

The digital-exhibit-lab template repository contains:

- documentation for instructors (in the "docs" folder, starting with this file!)
- a fully configured version of [CollectionBuilder-Sheets](https://github.com/CollectionBuilder/collectionbuilder-sheets), that will generate a digital exhibit from your project metadata
- template guideline pages for the learners that are published as part of the exhibit website (in "pages/project/" folder)

Instructors will make a copy of the template to configure and customize for their specific context and learning objectives.

The digital-exhibit-lab template repository can be copied on GitHub to quickly set up your customized Digital Exhibit Lab instance.
GitHub's platform has free, builtin features to edit the project code, set up collaborative project management, and host your exhibit website.

## Framing your project

Digital Exhibit Lab can be framed in different ways depending on which aspects of the archival research and digital scholarship you want to focus on, 
and the technical level of the instructors and students (and which digital skills you want to build).
The first step to getting started is thinking about how you want to frame the project.

To create the final digital exhibit, students will need a set of digital objects and metadata. 
The template is flexible enough to accommodate digital objects from a variety of sources:

- objects hosted in the repository -- .jpg, .pdf, or .mp3 files are added to the "objects" folder of your repository.
- YouTube and Vimeo videos -- IDs referencing the videos are added to the metadata, allowing the exhibit to display them.
- external object links -- objects hosted anywhere online where you can get a direct URL to the web accessible file (images, pdfs, mp3s, videos) can be added to the metadata. This provides a lot of flexibility to curate items from existing repositories without needing to add any files to the project.

Metadata describing the set of objects will be created in a spreadsheet.
For a collaborative online option, this can be done using Google Sheets.
The exhibit website can directly load the metadata from Google Sheets (so that edits can be seen in realtime), other web accessible CSVs, or a CSV added to the project repository.

How you gather the aggregation of items for the exhibit can change focus of the assignment.
Some possible options include:

- Archival research and digitization -- visiting the archives (special collections or museum), students do archival research. They select objects for the collection, then work on the digitization and create metadata.
- Digitization and metadata -- working from a pre-selected set of items, students work on digitizing objects and creating metadata for the collection.
- Digital research and curation -- students do archival research in online repositories. They select objects from existing digital collections to add to their exhibit and create contextualized metadata.
- Metadata and description -- working from a pre-selected set of digitized items, students focus on creating metadata for the collection to create the exhibit features.

The minimal computing approach of digital-exhibit-lab allows the final exhibit website to be set up using the free services on GitHub without needing to maintain any central infrastructure (or on your own minimal server).
This means the template is also flexible enough to accommodate several arrangements for creating the final exhibit website:

- One shared course collection -- students create/describe their own set of items and contribute all items to one central collection. This allows students to participate without needing to know anything about GitHub or the project repository, focusing on digitization/curation and metadata work in a spreadsheet. The final exhibit will be a rich aggregation with contributions from all students.
- Group collections -- exhibits can be created as small group work, where members can work together to create a shared collection. Group members can take ownership over the initial set up and configuration of their project repository, exposing them to more the technical underpinning of the project, while still keeping most of the focus on digitization/curation and metadata work in a spreadsheet. The course will be able to compare how different groups curated unique set of items, described them differently, or presented different features.
- Individual collections -- in contexts where students would like to learn more technical skills or invest significant time in their own personalized collection, each individual could create their own copy of the course's Digital Exhibit Lab template. This would put the focus on students learning more about working with GitHub and give them ownership over their own web property. 
- Long term shared collection - if a course is repeated over time, another option would be to have an ongoing collection that students continue to contribute to. This allows students to build on previous work and create a unique record of their research that has ongoing use.

Once you have decided on the parameters of your project, you are ready to set up your repository(s)!

## Get Started

- [Start a new project repository "start-a-project.md"](start-a-project.md)
- [Initial project setup "initial-setup.md"](initial-setup.md)
- [Set up metadata spreadsheet "sheets-metadata-logistics.md"](sheets-metadata-logistics.md)

## Resources

- Example assignment ["Mining the Archives" document](mining-the-archive-project.md), corresponding to [hist-454-2022 repository](https://github.com/thecdil/hist-454-2022) and [hist 454 exhibit](https://thecdil.github.io/hist-454-2022/)
- Ask questions at [digital-exhibit-lab discussion forum](https://github.com/learn-static/digital-exhibit-lab/discussions)
- [CollectionBuilder-Sheets](https://github.com/CollectionBuilder/collectionbuilder-sheets) and [CollectionBuilder Documentation](https://collectionbuilder.github.io/cb-docs/)

## Potential Sources for Curation

look for public domain collections

Farm Security Administration/Office of War Information Black-and-White Negatives
https://www.loc.gov/collections/fsa-owi-black-and-white-negatives/
find an item of interest,
collection uses IIIF, however for our purposes the basic preview image will work well.
https://www.loc.gov/item/2017826254/
below the image preview, look for the "Download" option. Select the largest JPEG option, click go. This should open the image in a new tab. Copy the link from that tab into metadata "filename" field
alternatively, right click on the image, select "copy image address".

Chronicling America newspapers
https://chroniclingamerica.loc.gov/lccn/sn88078386/1922-05-05/ed-1/seq-1/
view item, look above the page image for download links, copy the "PDF" link, paste into metadata "filename" field

Smithsonian Open Access
https://www.si.edu/openaccess
find item of interest, 
https://www.si.edu/object/shoshone-falls-snake-river-idaho-view-across-top-falls:saam_1994.91.141
collection uses IIIF, however for our purposes the basic preview image will work well.
right click on the image, select "copy image address", paste the link into the metadata "filename" field.
(don't use the download button, since this preps the file differently and will not work)
alternatively, click the IIIF icon, click "manifest".
in the JSON you will eventually find a value in sequences > canvases > images > resource > id, that looks like a link to a .jpg file,
https://ids.si.edu/ids/iiif/SAAM-1994.91.141_2/full/full/0/default.jpg
copy this link, paste into metadata "filename" field.

For collections that use IIIF, for a more advanced class you could introduce the idea of APIs and how IIIF works. 
Each of these websites will have a recipe to construct a URL to get images from their IIIF server. 
Rather than copying and pasting from the item pages, students could figure out the IIIF recipes to find an image link.
Since they follow the IIIF standard, the API patterns are the same on any site, once you figure out the correct server URL and item ID.
