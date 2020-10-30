# code-refactor
The purpose of this project was to improve accessibility by ensuring it meets accessibility standards and fixing any items that did not meet those standards at the onset of the project. Failure to meet accessibility standards  opens the company up to potential litigation for failing to provide equal accessibility of the site to disabled users. The site meets with specified accessibility standards as a result of this project.

 In addition to meeting accessibility standards; the website, HTML and CSS were also reviewed to determine if there were any areas of improvement to support the accessibility as well as functionality of the site. In addition to fixing any accessibility issues, this review yeilded several improvements to functionality and streamlined the code. A summary complete changes are noted below, specific changes are commentted within the files for better understanding.

Issue | Solution | Result
------------- | ------------ | -------------
 |  |
**HTML _(Includes Accessibility Errors)_** |  |
Title of the page was not defined | replace "website" with more appropriate title | Title is now the company name "Horiseon"
Search Engine Optimization link in header did not work | Added missing id attribute to corresponding article element | Link navigates to the SEO content lower on the page
Abundant use of divs, impacting accessibility negatively | Convert divs to semantic elements | Improved accessiblity and SEO ranking
Images did not have alt attributes | Add alt attribute and define | Accessible alt attributes
Copyright out of date | Update to current year | Updated copyright date
 |  |
**CSS** |  |
Classes used with divs rather than sections | Convert div classes to styles applied to specific semantic elements or the tags within those elements | consolidate and reduce amount of styles needed
Three identical and individual classes (.search-engine-optimization, .online-reputation-management, .social-media-marketing) created for application to the corresponding content div tags | Consolidate code to apply to the article element | Reduced 3 style classes to 1 style applied based on semantic element
Three identical and individual classes (.search-engine-optimization, .online-reputation-management, .social-media-marketing) created for application to the corresponding content img tags | Consolidate code to apply to the img tag within the article element | Reduced 3 style classes to 1 style applied based on tag and specific semantic element
Three identical and individual classes (.search-engine-optimization, .online-reputation-management, .social-media-marketing) created for application to the corresponding content h2 tags | Consolidate code to apply to the h2 tag within the article element | Reduced 3 style classes to 1 style applied based on tag and specific semantic element
Three identical and individual classes (.benefit-lead, .benefit-brand, .benefit-cost) created for application to the corresponding content div tags | Consolidate code to apply to the aside element | Reduced 3 style classes to 1 style applied based on semantic element
Three identical and individual classes (.benefit-lead, .benefit-brand, .benefit-cost) created for application to the corresponding content img tags | Consolidate code to apply to the img tag within the aside element | Reduced 3 style classes to 1 style applied based on tag and specific semantic element
Three identical and individual classes (.benefit-lead, .benefit-brand, .benefit-cost) created for application to the corresponding content h3 tags | Consolidate code to apply to the h3 tag within the aside element | Reduced 3 style classes to 1 style applied based on tag and specific semantic element
CSS styles flow did not follow the sturcture of the HTML elements | Group CSS styles according to their place in the HTML | CSS styles now appear/flow according to the structure of the HTML and how/when they should render