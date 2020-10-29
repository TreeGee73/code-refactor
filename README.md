# code-refactor
The purpose of this project was to improve accessibility by ensuring it meets accessibility standards and fixing any items that did not meet those standards at the onset of the project. Failure to meet accessibility standards  opens the company up to potential litigation for failing to provide equal accessibility of the site to disabled users. The site meets with specified accessibility standards as a result of this project.

 In addition to meeting accessibility standards; the website, HTML and CSS were also reviewed to determine if there were any areas of improvement to support the accessibility as well as functionality of the site. In addition to fixing any accessibility issues, this review yeilded several improvements that improved functionality and streamlined the code. The complete changes are noted below.

Issue | Solution | Result
------------- | ------------ | -------------
**HTML _(Includes Accessibility Errors)_** |  |
Images did not have alt attributes | add alt attribute and define | accessible alt attributes
Search Engine Optimization link in header did not work | Added missing id to div tag | Link navigates to the SEO content lower on the page
Title of the page was not defined | replace "website" with more appropriate title | Title is now the company name "Horiseon"
**CSS** |  |
Individual classes .search-engine-optimization, .online-reputation-management, & .social-media-marketing for the div, img, & h2 tags with identical styling | Consolidate code for to apply to the tag only based on the container's div class of .content | Reduced 9 styles classes to 3 styles applied based on tag
Individual classes .benefit-lead, .benefit-brand, & .benefit-cost for the div, img, & h3 tags with identical styling | Consolidate code for to apply to the tag only based on the container's div class of .benefits | Reduced 9 styles classes to 3 styles applied based on tag
CSS styles flow did not follow the sturcture of the HTML elements | Group CSS styles according to their place in the HTML | CSS styles now appear/flow according to the structure of the HTML and how/when they should render