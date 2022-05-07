# Digital Exhibit Lab Overview for Instructors

Digital Exhibit Lab is a Learn-Static template for creating an assignment that gives students hands-on experience creating a digital collection. 

The digital-exhibit-lab template repository contains:

- documentation for instructors (in the "docs" folder, starting with this file!).
- template guideline pages for the learners that are published as part of the exhibit website (in "pages/project/" folder, or view the [demo guidelines](https://learn-static.github.io/digital-exhibit-lab/project/overview.html)).
- a fully configured version of [CollectionBuilder-Sheets](https://github.com/CollectionBuilder/collectionbuilder-sheets), that will generate a digital exhibit from your project metadata.

Instructors will make a copy of the template to configure and customize for their specific context and learning objectives.

The digital-exhibit-lab template repository can be copied on GitHub to quickly set up your customized Digital Exhibit Lab instance.
GitHub's platform has free, builtin features to edit the project code, set up collaborative project management, and host your exhibit website.

For more information about CollectionBuilder and how it works, please see the [CollectionBuilder About page](https://learn-static.github.io/digital-exhibit-lab/project/overview.html).

## Framing your Project

Digital Exhibit Lab can be framed in different ways depending on which aspects of the archival research and digital scholarship you want to focus on, 
and the technical level of the instructors and students (and which digital skills you want to build).
The first step to getting started is thinking about how you want to frame the project.

### Objects and Metadata

To create the final digital exhibit, students will need a set of digital objects and metadata. 
The template is flexible enough to accommodate digital objects from a variety of sources:

- objects hosted in the repository -- .jpg, .pdf, or .mp3 files are added to the "objects" folder of your repository.
- YouTube and Vimeo videos -- IDs referencing the videos are added to the metadata, allowing the exhibit to display them.
- external object links -- objects hosted online anywhere you can get a direct URL to the web accessible file (images, pdfs, mp3s, videos) can be added to the metadata. This provides a lot of flexibility to curate items from existing repositories without needing to add any files to the project.

Metadata describing the set of objects will be created in a spreadsheet.
For a collaborative online option, this can be done using Google Sheets.
The exhibit website can directly load the metadata from Google Sheets (so that edits can be seen in realtime), other web accessible CSVs, or a CSV added to the project repository.

How you gather the aggregation of items for the exhibit can change focus of the assignment.
Some possible options include:

- Archival research and digitization -- visiting the archives (special collections or museum), students do archival research. They select objects for the collection, then work on the digitization and create metadata.
- Digitization and metadata -- working from a pre-selected set of items, students work on digitizing objects and creating metadata for the collection.
- Digital research and curation -- students do archival research in online repositories. They select objects from existing digital collections to add to their exhibit and create contextualized metadata.
- Metadata and description -- working from a pre-selected set of digitized items, students focus on creating metadata for the collection to create the exhibit features.

### Exhibit Approach

The minimal computing approach of digital-exhibit-lab allows the final website to be set up using the free services on GitHub without needing to maintain any central infrastructure (alternatively, if you do want to self host the collection, only a minimal server is required, and there is no server side application to install or maintain).
This means the template is also flexible enough to accommodate several arrangements for creating the final exhibit website:

- One shared course collection -- students create/describe their own set of items and contribute all items to one central collection. This allows students to participate without needing to know anything about GitHub or the project repository, focusing on digitization/curation and/or metadata work in a spreadsheet. The final exhibit will be a rich aggregation with contributions from all students.
- Group collections -- exhibits can be created as small group work, where members can work together to create a shared collection. Group members can take ownership over the initial set up and configuration of their project repository, exposing them to more the technical underpinning of the project, while still keeping most of the focus on digitization/curation and metadata work in a spreadsheet. The course will be able to compare how different groups curated unique sets of items, described them differently, or presented different features.
- Individual collections -- in contexts where students would like to learn more technical skills or invest significant time in their own personalized collection, each individual could create their own copy of the course's Digital Exhibit Lab template. This would put the focus on students learning more about working with GitHub and give them ownership over their own web property. 
- Long term shared collection - if a course is repeated over time, another option would be to have an ongoing collection that students continue to contribute to. This allows students to build on previous work and create a unique record of their research that has ongoing use.

### Project Preparation 

The Digital Exhibit Lab template is designed to be "doable" for librarians and digital humanities practitioners.
You may not be familiar with the tools and technology generating the website, but learning it shouldn't be much more difficult than adopting any other web platform such as Omeka or WordPress--yet the very low infrastructure requirements and minimal computing approach will provide many advantages for simplicity and sustainability over those complicated server-side applications.
This provides many options for how to spin up the project--you do not need IT support.
A librarian or DH center employee could set up and coordinate the project for teaching faculty, minimizing the prep time necessary to integrate in the classroom. 
Or anyone with time to learn (from instructor to student) could follow the detailed [CollectionBuilder documentation](https://collectionbuilder.github.io/cb-docs/) to complete the necessary configuration, maximizing the learning of the technical workflows.

Once you have decided on the parameters of your project, you are ready to set up your repository(s)!

## Get Started

- [Start a new project repository - "start-a-project.md"](start-a-project.md)
- [Initial project setup - "initial-setup.md"](initial-setup.md)
- [Set up metadata spreadsheet - "sheets-metadata-logistics.md"](sheets-metadata-logistics.md)
- [Collection objects and curation options - "collection-objects.md"](collection-objects.md)

## Resources

- Example assignment ["Mining the Archives" document](mining-the-archive-project.md), corresponding to [hist-454-2022 repository](https://github.com/thecdil/hist-454-2022) and [hist 454 exhibit](https://thecdil.github.io/hist-454-2022/)
- Ask questions at [digital-exhibit-lab discussion forum](https://github.com/learn-static/digital-exhibit-lab/discussions)
- [CollectionBuilder-Sheets](https://github.com/CollectionBuilder/collectionbuilder-sheets) and [CollectionBuilder Documentation](https://collectionbuilder.github.io/cb-docs/)
