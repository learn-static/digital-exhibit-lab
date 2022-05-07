# Digital Exhibit Lab Metadata 

Metadata is central to any Digital Exhibit Lab project. 
Metadata describing the collection objects is created in a spreadsheet, which drives the generation of features on the exhibit website. 

To get started, make a copy of the metadata template either on Google Sheets or via the CSV file:

- [Copy the Metadata Template on Google Sheets](https://docs.google.com/spreadsheets/d/16ZxZ7yhFVne6rChY7frpzDN94sthAKsRU1UOvprwgzk/copy?usp=sharing)
- Copy the ["metadata_template.csv"](metadata_template.csv)

The digital-exhibit-lab template is configured to work with the fields in this spreadsheet, and the use of each field is described in the [Metadata Guidelines page](https://learn-static.github.io/digital-exhibit-lab/project/metadata.html).
Students can follow along step-by-step with the guidelines to create metadata records for their objects.

You can tweak the [configuration options (following CollectionBuilder docs)](https://collectionbuilder.github.io/cb-docs/docs/customization/) to accommodate any metadata fields you can think up!
Just be sure to update your project's copy of the metadata template and details in "page/project/metadata.md".

## Course Logistics

Depending on how you frame your project, you will want to set up a means to collaborate on the metadata spreadsheet. 

The [template guidelines](https://learn-static.github.io/digital-exhibit-lab/project/metadata.html) assume the student will draft their own metadata using Google Sheets, then contribute their records to a single shared Google Sheet that is used by the exhibit website.
We find this two step process avoids confusion on actively working in a shared spreadsheet.
Students also have the opportunity to [test their metadata](https://learn-static.github.io/digital-exhibit-lab/project/setup.html), temporarily replacing the metadata on the live site.

The [spreadsheet guidelines](https://learn-static.github.io/digital-exhibit-lab/project/spreadsheets.html) provide helpful tips for working with spreadsheets to ensure students have resources to develop these essential data skills.

You may want to change this workflow depending on the objectives of your project--Google Sheets is a handy option, not a requirement!

## Configure Exhibit Metadata

CollectionBuilder-Sheets loads and parses a metadata CSV directly to create your digital collection pages. 
When you visit the exhibit website in a new browser window, it downloads the metadata, temporarily stores it in the browser, and uses it to generate the visualization features on each page.
To refresh the metadata, simply open the exhibit in a new browser window.

To set up the exhibit site, prep your metadata following the template, then reference it's location in the "_config.yml" `metadata-csv` option, and you are ready to go!

You have three main options for your metadata CSV:

- Google Sheets (helpful for live collaboration and testing of metadata)
- a CSV directly in your project (a good option at the end of the project, once the metadata is complete)
- a CSV available on the web

### Set up Google Sheets

Set up a Google Sheet with metadata following the template.
Be especially careful with column names in the first row!
They need to have no spaces and no extra white space at the end of the value (and exactly match what you have used in configuring your collection site).

On the Google Sheet, go to File > Publish to the Web.
On the popup modal, use the dropdowns in "Link" tab to select the sheet name of your metadata (usually "Sheet 1") and "Comma-separated values (.csv)" options, then click "Publish" button.
Copy the link that is provided.

Paste link into "_config.yml" as value for `metadata-csv`.

For example: 

`metadata-csv: https://docs.google.com/spreadsheets/d/e/2PACX-1vSn7AA-cbsXT3_nNUGftc1ab-CKXOJHMQCIENeR9NHElbyI9_qA99o0-HNZdG04v-M2_N21bUe_krQQ/pub?gid=0&single=true&output=csv`

### Use CSV in Project

Your CSV can also be hosted directly in your project repository.
Often this is a CSV downloaded from Google Sheets after the metadata is complete.
We suggest creating your CSV using OpenRefine, Sheets, or LibreOffice Calc (and do not suggest using Excel, since Excel's CSV output is not correctly formatted).

Copy your CSV file into the "assets" folder then reference it in the "_config.yml" using a relative path. 

For example:

`metadata-csv: /assets/demo-metadata.csv`

### Set up Web CSV

If you have a CSV available anywhere on the web, you can use it by referencing the full URL. 

For example:

`metadata-csv: https://www.lib.uidaho.edu/collectionbuilder/demo-metadata.csv`

Please ensure your CSV is correctly formatted and encoded (UTF-8), being especially careful with the column names.
We suggest creating your CSV using OpenRefine, Sheets, or LibreOffice Calc (and do not suggest using Excel, since Excel's CSV output is not correctly formatted).

To use a CSV hosted in a GitHub repository, use the "raw" link.

`metadata-csv: https://raw.githubusercontent.com/CollectionBuilder/collectionbuilder-sample-data/master/psychiana_cbdemo_gh.csv`

*Note:* depending on where your CSV is hosted, you may encounter [CORS errors](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS/Errors).
