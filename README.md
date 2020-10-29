# code-refactor
At a minimum, your project README needs a title and a short description explaining the what, why, and how. What was your motivation?Why did you build this project? (Note: The answer is not "Because it was a homework assignment.") What problem does it solve? What did you learn? What makes your project stand out?

The purpose of this project was to improve accessibility by ensuring it meets accessibility standards and fixing any items or code that did not meet those standards at the onset of the project.This is an important consideration for web developers as websites that do not meet accessibility standards do not render properly (if at all) for disabled users. This opens your client/company up to potential litigation for failing to meet these standards and offer a fully accessible site to disabled users. Once reviewed, it was determined... and the site meets accessibility standards...

 In addition to meeting accessibility standards; the Site, site's HTML and CSS were reviewed to determine if there were any areas of improvement to support the accessibility as well as functionality of the site. As a result of this review several improvements were made that improved functionality and streamlined the code. The complete changes are noted below.

Issue | Solution | Result
------------- | ------------ | -------------
HTML (Includes Accessibility Errors) |  |
Images did not have alt attributes | add alt attribute and define | accessible alt attributes
Search Engine Optimization link in header did not work | Added missing id to div tag | Link navigates to the SEO content lower on the page
Title of the page was not defined | replace "website" with more appropriate title | Title is now the company name "Horiseon"
CSS |  |
Individual classes .search-engine-optimization, .online-reputation-management, & .social-media-marketing for the div, img, & h2 tags with identical styling | Consolidate code for to apply to the tag only based on the container's div class of .content | Reduced 9 styles classes to 3 styles applied based on tag
Individual classes .benefit-lead, .benefit-brand, & .benefit-cost for the div, img, & h3 tags with identical styling | Consolidate code for to apply to the tag only based on the container's div class of .benefits | Reduced 9 styles classes to 3 styles applied based on tag
CSS styles flow did not follow the sturcture of the HTML elements | Group CSS styles according to their place in the HTML | CSS styles now appear/flow according to the structure of the HTML and how/when they should render