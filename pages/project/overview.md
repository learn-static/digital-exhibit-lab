---
title: Project Overview
layout: page-narrow
permalink: /project/overview.html
---

{% include feature/jumbotron.html objectid="https://objects.lib.uidaho.edu/watkins/small/watkins56_sm.jpg" %}

# Digital Exhibit Lab Overview

Instructions for learners are published as part of your *Digital Exhibit Lab* project website.
This demo site provides some example instructions and guidelines specific to a classroom experience.
Instructors will customize these pages to their specific context and assignment details.

*Digital Exhibit Lab* project involves several components:

- **Archival Research:** Working with [U of I Special Collections and Archives](https://www.lib.uidaho.edu/special-collections/), explore and do hands on research with primary source materials related to mining. Highlighted materials include:
    - [Bunker Hill Company records, 1887-1984](http://archiveswest.orbiscascade.org/ark:/80444/xv65328)
    - [Stanly Easton Papers, 1900-1957](https://archiveswest.orbiscascade.org/ark:/80444/xv66353)
    - [Barnard-Stockbridge Ledgers and Other Papers, 1888-1989](https://archiveswest.orbiscascade.org/ark:/80444/xv01033)
- **Digitization:** From your archival research, select at least one photograph and one text source to digitize. Working with the [Center for Digital Inquiry and Learning](https://cdil.lib.uidaho.edu/) (CDIL), scan your selected items and prepare digital files.
- **Curation:** Explore [U of I Library Digital Collections](https://www.lib.uidaho.edu/digital/collections.html) and select five additional items from existing digital collections.
- **Description and Metadata:** Create metadata following the collection template to describe your digitized and curated items.
- **Exhibit:** Once all objects and metadata are submitted, CDIL generates the final digital exhibit (this site!). 
- **Research and Reflection:** Write your course papers and reflections informed by your archival research and project experience.

The sections below provide an overview of the project digital collection project components and the learning objectives.

## Digitization 

> *digitize*, v. to transform analog information into digital form ([SAA Dictionary](https://dictionary.archivists.org/entry/digitize.html))
{:.blockquote .border-left .pl-3 .lead .my-3}

Digitization is the process of creating a digital representation of physical materials--for example, scanning a photograph to create a digital JPEG image or scanning using OCR on a print document to create a PDF.
In the digital files we create and the information we publish, we strive to represent the original source materials and maintain the integrity of the records as accurately as possible.
By converting physical information into a digital format, digitization can open up more access to traditional archival materials and enable new forms of inquiry and communication.

We often take for granted the millions of archival documents and artifacts available online, without thinking about the long chain of people and processes that created them.
Digitization in archives has transformed historical research in many ways, so it is important to understand and think critically about.

This project asks you to get hands on with that process, bringing physical materials from the archive into the digital world.

See [Digitization Guidelines]({{ '/project/digitization.html' | relative_url }}) for details.

## Curation

No collection can contain and represent everything from the relevant historical record. 
Selections and interventions were made a multiple points along the trajectory of each record, from the original creators, to natural disasters, to the collecting organizations, to the archivists, to the historians sifting through boxes...
Each of these choices bring biases, [archival silences](https://dictionary.archivists.org/entry/archival-silence.html), and new interpretations.

In this project you will also be making selections, mining the archive to curate a small set of records relevant to the course research project.
Your first act of curation is selecting your objects for digitization from the archives.
We would like you to go further, enhancing the final *Digital Exhibit Lab* collection by selecting five items from U of I digital collections relevant to your research questions.

While digging into the existing digital archives, consider how this process is different than your experience working with the physical archives in Special Collections.

See [Curation Guidelines]({{ '/project/curation.html' | relative_url }}) for details.

## Description & Metadata 

> *description*, n., a set of data crafted to identify and represent an archival resource or component thereof ([SAA Dictionary](https://dictionary.archivists.org/entry/description.html))
>
> *descriptive metadata*, n., Information that refers to the intellectual content of material and aids discovery of such materials. Notes: Descriptive metadata allows users to locate, distinguish, and select materials on the basis of the material's subjects or 'aboutness.' ([SAA Dictionary](https://dictionary.archivists.org/entry/descriptive-metadata.html))
{:.blockquote .border-left .pl-3 .lead .my-3}

Description and metadata is essential to archives and digital collections, profoundly impacting user experience, discoverability, and bias. 
The practice of creating metadata is an act of research and interpretation.
This assignment seeks to build a thoughtful and critical understanding of finding aids and digital collections, by actually creating metadata yourself.

The practice of describing objects is a rich subject of academic study--so there is a lot to think critically about--but an important take away is simply that metadata is made by humans like you!
As metadata creators, we seek to do our best to represent the important information about the archival materials in the context of the collection--creating metadata that will help future users (and yourselves) find, contextualize, and understand the objects in the collection.

This project will use a standard metadata template providing the set of descriptive fields for all items to ensure consistency across the collection.
The fields are based on [Dublin Core](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/) and other standards and conventions used in digital libraries. 
Following standards helps our metadata be compatible with other systems, helps other people understand our descriptive practice, and helps users find what they are looking for.

For example, each column below contains exactly the same info:

| 2015-10-14 | $1,000 | ID |
| 10/14/2015 | 1000 | I.D. |
| 10/14/15 | 1,000 | US-ID |
| Oct 14, 2015 | 1000 dollars | idaho |
| Wed, Oct 14th | US$1000 | Idaho, |
| 42291 | $1k | Ihaho |
{:.table .table-bordered}

A human looking at these values can read them successfully, however in a digital system the inconsistent formatting of the data will make it harder for users to discover relevant and related materials.

Explore the demo collection and metadata to understand how the field values are used to generate browsing features in the exhibit site.
Consider the implications of the choices of which fields to include in the template, and which words you use to describe your objects.
Take a close look at the metadata guidelines to review important concepts embedded in the template, such as "subject" about-ness, "identifiers" referring back to physical collections, and "rightsstatement" containing intellectual property information.

See [Metadata Guidelines]({{ '/project/metadata.html' | relative_url }}) for details.

## Digital Exhibit

> *online exhibition*, n. a curated display of archival resources accessible via the internet. Notes: Not simply a digital collection, an online exhibition is a collection of interrelated archival resources focused around a theme. ([SAA Dictionary](https://dictionary.archivists.org/entry/online-exhibition.html))
{:.blockquote .border-left .pl-3 .lead .my-3}

Everyone's work on the project will contribute to the *Digital Exhibit Lab* digital exhibit.
Once objects and metadata are complete, the CDIL team will add them to the [project repository](https://github.com/thecdil/hist-454-2022) hosted on GitHub, publishing our final collection.
The objects on this site can be used and cited in your research writing.

Consider how the shift in context, from separate archival boxes and multiple collections, to this new exhibit has impacted the interpretation and understanding of the items.

### CollectionBuilder

This project is based on [CollectionBuilder](https://collectionbuilder.github.io/), an open source tool for creating digital collection and exhibit websites that are driven by metadata and powered by modern static web technology.
CollectionBuilder is used to create [digital collections](https://www.lib.uidaho.edu/digital/), teach in classes, and [collaborate with researchers](https://cdil.lib.uidaho.edu/projects/).
