# Web-Design-Challenge

This repo contains a website with 7 pages total with links, including:

* A landing page containing:
  * An explanation of the project.
  * Links to each visualizations page. There is also a sidebar containing preview images of each plot, by clicking on the image the user can go to that visualization.

* Four visualization pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.

* A "Comparisons" page that:
  * contains all of the visualizations on the same page so we can easily visually compare them.

* A "Data" page that:
  * Displays a responsive table containing the data used in the visualizations.

* The data comes from exporting the `.csv` file and converting to HTML using python pandas library. 

The website has at the top of every page, a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). 

Finally, the website is deployed to GitHub pages.

