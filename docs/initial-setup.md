# Initial Digital Exhibit Lab Set up

Once you have a copy of the digital-exhibit-lab template in your own repository (see "start-a-project.md"), there is some initial set up to get your project ready.

## Activate GitHub Pages

Digital Exhibit Lab is designed to be built and hosted by the free GitHub Pages service. 
To start generating your project site, you will want to active GitHub Pages:

1. On your project repository's home page, click the "Settings" button (appears on the right along the tabs above the code area).
2. On "Settings" page: click "Pages" in the left side menu.
3. On the "Pages" page: in the "Source" section, change the dropdown button from "none" to "main" (leave the folder option as "/root"), then click the "Save" button. 

Once saved, the page will refresh with an alert providing the URL where your site will appear. 
It will take a few minutes for the build to happen and your site to go live--so wait it out! 
Once activated, GitHub Pages will rebuilt the site each time you make a new commit in the project.

For more details, see [CollectionBuilder GH deploy](https://collectionbuilder.github.io/cb-docs/docs/deploy/gh-pages/).

*Note:* using GitHub Pages is NOT required--it is just very handy!
Your site can be built and hosted using other automatic online services or manually using Jekyll on your local machine.

## Edit "_config.yml"

The main settings for your site are contained in the "_config.yml" file.
This is where you will give your project a title and set the metadata file to use.

Please follow the [CollectionBuilder Configuration documentation](https://collectionbuilder.github.io/cb-docs/docs/config/) to fill in the options.

See ["metadata-logistics.md"](metadata-logistics.md) for options to use as `metadata-csv` value.

## Further Customization

Digital Exhibit Lab is pre-configured to to work with the fields used in the "metadata_template.csv".
If you want to change which fields are displayed and which visualizations are listed in the navigation, please check the [CollectionBuilder page customization documentation](https://collectionbuilder.github.io/cb-docs/docs/customization/).

You can also tweak the basic look of your site using the ["theme.yml" options](https://collectionbuilder.github.io/cb-docs/docs/theme/).
