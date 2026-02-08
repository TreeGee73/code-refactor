# Code Refactor

---

## 📚 Educational Project

This project was completed as part of University of Arizona Full-Stack Web Development Bootcamp to demonstrate understanding of: **web accessibility standards (WCAG), semantic HTML elements, CSS optimization and consolidation, code refactoring best practices, and SEO improvement techniques**.

**Status:** Archived - No longer under active development  
**Purpose:** Portfolio demonstration of accessibility compliance and code quality improvement  
**Completed:** October 2020

---

## Table of Contents
  * [Description](#description)
  * [Usage](#usage)
  * [Technology](#technology)
  * [Questions / Contact Details](#questions--contact-details)

---

## Description

The purpose of this project was to improve accessibility by ensuring the website meets accessibility standards and fixing any items that did not meet those standards at the onset of the project. Failure to meet accessibility standards opens the company up to potential litigation for failing to provide equal accessibility of the site to disabled users. The site meets specified accessibility standards as a result of this project.

In addition to meeting accessibility standards, the website HTML and CSS were also reviewed to determine if there were any areas of improvement to support the accessibility as well as functionality of the site. This review yielded several improvements to functionality and streamlined the code.

### Key Improvements

#### HTML (Includes Accessibility Fixes)
| Issue | Solution | Result |
|-------|----------|--------|
| Title of the page was not defined | Replaced "website" with more appropriate title | Title is now the company name "Horiseon" |
| Search Engine Optimization link in header did not work | Added missing id attribute to corresponding article element | Link navigates to the SEO content lower on the page |
| Abundant use of divs, impacting accessibility negatively | Converted divs to semantic elements | Improved accessibility and SEO ranking |
| Images did not have alt attributes | Added alt attribute and defined descriptive text | Accessible alt attributes for screen readers |
| Copyright out of date | Updated to current year | Updated copyright date |

#### CSS Optimization
| Issue | Solution | Result |
|-------|----------|--------|
| Classes used with divs rather than sections | Converted div classes to styles applied to specific semantic elements or the tags within those elements | Consolidated and reduced amount of styles needed |
| Three identical classes (.search-engine-optimization, .online-reputation-management, .social-media-marketing) for content div tags | Consolidated code to apply to the article element | Reduced 3 style classes to 1 style applied based on semantic element |
| Three identical classes for content img tags | Consolidated code to apply to the img tag within the article element | Reduced 3 style classes to 1 style applied based on tag and semantic element |
| Three identical classes for content h2 tags | Consolidated code to apply to the h2 tag within the article element | Reduced 3 style classes to 1 style applied based on tag and semantic element |
| Three identical classes (.benefit-lead, .benefit-brand, .benefit-cost) for sidebar div tags | Consolidated code to apply to the aside element | Reduced 3 style classes to 1 style applied based on semantic element |
| Three identical classes for sidebar img tags | Consolidated code to apply to the img tag within the aside element | Reduced 3 style classes to 1 style applied based on tag and semantic element |
| Three identical classes for sidebar h3 tags | Consolidated code to apply to the h3 tag within the aside element | Reduced 3 style classes to 1 style applied based on tag and semantic element |
| CSS styles flow did not follow the structure of the HTML elements | Grouped CSS styles according to their place in the HTML | CSS styles now appear/flow according to the structure of the HTML and how/when they should render |

---

## Usage

This is a static marketing website for Horiseon, a digital marketing agency. The site features:
- Accessible navigation with working anchor links
- Semantic HTML structure for improved accessibility
- Optimized CSS for better performance
- SEO-friendly markup

---

## Technology

* **HTML** (56%) - Semantic structure and accessibility
* **CSS** (44%) - Styling and layout optimization

---

## Questions / Contact Details

If you have any questions about this project, please visit my GitHub profile at [TreeGee73](https://github.com/TreeGee73).
