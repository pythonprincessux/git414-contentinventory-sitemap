# Acceptance Criteria Starter

Use this structure:

> When [condition], [content/component/page] must [observable behavior] so that [user/task/quality goal]. I will test this by [test method].

## Criteria Drafts

1. Responsive: When Beyond the Rent is viewed at 320 CSS px wide, the navigation and main content must fit without page overflow or horizontal scrolling so that renters/visitors can read and navigate on small screens mobile screens when necessary. I will test this using Chrome DevTools in responsive mode/mobile view at 320 px and test every page for overflow.

2. Responsive: When the browser is zoomed in to 200%, the rental fee explanations and all page content should still remain readable without clipped or overlapping text so that visitors can zoom in on the content and still read it without any issues.  I will test this in chrome by setting browser zoom to 200% and going through every page.

3. Accessibility: When a user is using only the keyboard for the page, every link should have a visible focus indicator (gold) and follow a logical order so that users using only a keyboard will know what is selected and what they are looking at. I will test this using the following buttons: Tab, Shift+Tab, the space bar and Enter on every page.

4. Accessibility: When a visitor reads the table with a screen reader, every sample cost should have its own associated heading announced so that the visitor can know the amounts. I will test this by inspecting the table headers and navigating the table with the VoiceOver feature you can use in Safari.

5. Browser support or fallback: When the site is opened in Chrome, Firefox, and Safari, the navigation, fee explanations, comparison table, and checklist should remain usable so that visitors can complete the site's tasks across those browsers. I will test the published pages in each browser and record the results.

6. Performance: When a visitor loads any page, the transferred page resources must stay below 1 MB so that the informational guide is still fairly lightweight. I will test this using the browser Network panel with caching disabled and record the transferred size for each page.

7. Metadata or discoverability: When a visitor opens any page, the document will provide a unique, descriptive title and a page specific meta description so that the topic is identified to visitors and search engines. I will test this by inspecting each page's HTML head and its browser-tab title.

8. Release quality: When the site is published, all of the internal navigation links and resource links should reach its intended destination without a missing-page error so that users and renters can access the information they need. I will test this by opening every link on the published site and documenting any failures I see.

## AI Disclosure

For this week's assignment, I used ChatGPT to help suggest test methods for my Beyond the Rent capstone idea. I verified and rewrote all criteria myself. I completed all testing myself as instructed in the Canvas assignment directions.