# Content standards checklist

## For all VA.gov pages (including those in Resources and Support)

**Before you begin:**
- [ ] Confirm that there are no updates in draft by other content authors that aren't ready to be published. Check the revision log and then confirm with the content author who made the previous edits that the page is ready to publish.

### Accessibility standards

- [ ] Confirm all links contain a purpose and a target. A user will know from just the link text what the link does and where it is sending them. [Read more about making links accessible](https://www.accessibilityoz.com/2014/02/links-and-accessibility/) 
- [ ] Tell users where they'll land if your link will take them off VA.gov: Make sure the words in the text link, action link, or button indicate to the user that they're leaving VA.gov and where they're going.
- [ ] Confirm all phone numbers are in aria labels. [Learn how to code numbers with aria labels](https://design.va.gov/content-style-guide/dates-and-numbers#phone-numbers)
- [ ] Confirm that the heirarchy of headings is correct (H1 to H2 to H3—levels shouldn't be skipped). [Read WCAG documentation](https://www.w3.org/WAI/tutorials/page-structure/headings/) NOTE: After we add a link to this from our style guide entry for "Page titles and section titles", change this content checklist link to point to our style guide entry.

### Link standards

- [ ] Confirm that links work (aren't broken--no error message) and point to the intended page (you pasted in the correct URL or chose the correct node ID).
- [ ] Confirm all link text is 100 characters or less.
- [ ] Check that you've selected a node ID for all links pointing to VA.gov (internal) pages. Only paste in a URL if the page you're linking to does not live in our CMS (isn't one of our modernized pages). [Learn how to add node IDs in Drupal](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/teams/vsa/teams/sitewide-content/how-to-do-different-tasks/linking-with-node-ids.md) 

### Additional checks for Resources and Support articles

- [ ] Character limit for subheads: Confirm H2s, H3s, and H4s are within the 70-character limit.
- [ ] Related links: Confirm that you've added appropriate related links to the file (they should truly be related to the article—rather than “something the reader may also be interested in”).
- [ ] Cross linking: Determine if this new article should be added as a related link on any live articles. (Do you want to drive users to this page from elsewhere on VA.gov?)
- [ ] Call to action (CTA): When considering the wording for your CTA text, check to see if a label is already in use for this CTA on VA.gov. [Check the master list of labels for buttons and action links](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/teams/vsa/teams/sitewide-content/resources-and-support/rs-cta-button-audit.md)
- [ ] Confirm that there's alt text for screen shots: Check that any screenshots contain alt text that contain context. REVISE
- [ ] **For multiple FAQs:** First publish each single Q&A and then publish the multiple FAQ.

**Also confirm these components are checked in the Drupal file:**</br>
- [ ] The correct primary article category and additional article categories. 
- [ ] The correct benefit hub contacts. 
- [ ] The appropriate audience and topic tags. 
- [ ] "Repeat CTA buttons" box if it's a long article. This will display the action link at both the top and bottom of the page.
- [ ] **For a single Q&A:** "Enable standalone Resources and support page for this Q&A."
