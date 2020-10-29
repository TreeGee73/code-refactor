# code-refactor
At a minimum, your project README needs a title and a short description explaining the what, why, and how. What was your motivation?Why did you build this project? (Note: The answer is not "Because it was a homework assignment.") What problem does it solve? What did you learn? What makes your project stand out?



- [ ] GIVEN a webpage meets accessibility standards
- [ ] WHEN I view the source code
- [ ] THEN I find semantic HTML elements
- [ ] WHEN I view the structure of the HTML elements
- [ ] THEN I find that the elements follow a logical structure independent of styling and positioning
- [ ] WHEN I view the image elements
- [ ] THEN I find accessible alt attributes
- [ ] WHEN I view the heading attributes
- [ ] THEN they fall in sequential order
- [ ] WHEN I view the title element
- [ ] THEN I find a concise, descriptive title


The initial CSS code contained several instances of repeated formatting with individual class names. Consolidated into more concise multi-use classes, eliminating repetition.

Issue | Solution | Result
------------- | ------------ | -------------
Individual classes .search-engine-optimization, .online-reputation-management, & .social-media-marketing for the div, img, & h2 tags with identical styling | Consolidate code for to apply to the tag only based on the container's div class of .content | Reduced 9 styles classes to 3 styles applied based on tag
Individual classes .benefit-lead, .benefit-brand, & .benefit-cost for the div, img, & h3 tags with identical styling | Consolidate code for to apply to the tag only based on the container's div class of .benefits | Reduced 9 styles classes to 3 styles applied based on tag