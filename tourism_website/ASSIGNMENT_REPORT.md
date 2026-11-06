# DCOMP 204 — Web Design Assignment 2
## Development of a Responsive Multi-Page Website
### Project title: Explore Sierra Leone — Tourism Website

**Student name:** mohamed ibrahim bangura 
**Student ID:** 905006019
**Programme/Class:** DIT 1102
**Lecturer:** MR AMKAR
**Submission date:** 4-6

## 1. Introduction
Tourism can introduce visitors to Sierra Leone's beaches, islands, wildlife, cultural heritage and city life. The purpose of this project is to transform a tourism website design concept into a functional, responsive multi-page website using HTML, CSS and JavaScript.

## 2. Aim and objectives
The aim is to develop an accessible, attractive website that helps users discover tourism destinations and plan a responsible visit. Objectives are to provide five connected pages, apply consistent visual styling, support mobile/tablet/desktop layouts, use semantic HTML, provide basic interaction and organise source code for version control.

## 3. Target users
- Local and international visitors researching Sierra Leone.
- Students and families looking for destination ideas.
- People interested in beaches, nature, culture and heritage.

## 4. Website architecture
Home (`index.html`) links to Destinations, Experiences, Plan Your Trip and Contact. Every page shares the same header navigation and footer. This consistent structure makes the website easier to understand and navigate.

## 5. Page descriptions
**Home:** Introduces the tourism theme, includes a hero banner and previews featured places.  
**Destinations:** Describes River No. 2 Beach, Tiwai Island, Banana Islands and Freetown, with links to sections using anchor IDs.  
**Experiences:** Presents beach, nature, culture, heritage, island and community tourism.  
**Plan Your Trip:** Provides a client-side checklist, responsible travel tips and a sample three-day itinerary.  
**Contact:** Provides required fields for a name, email, topic and message. JavaScript displays a demonstration confirmation; no information is transmitted to a server.

## 6. Technologies
- **HTML5:** semantic page structure, headings, navigation, images, forms and labels.
- **CSS3:** colour palette, typography, grid/flex layouts, cards, spacing, hover/focus styles and responsive breakpoints.
- **JavaScript:** mobile navigation toggle and front-end contact form demonstration.
- **Git/GitHub:** recommended version control and source repository workflow.

## 7. Responsive design
The CSS uses a desktop-first layout with media queries at 850px and 560px. At narrower widths, navigation becomes a menu button, grids reduce from three columns to two or one, and multi-column sections stack. Images scale to container width and form controls remain usable on small screens. Testing was performed at desktop, tablet and mobile sizes.

## 8. Accessibility and code quality
The pages declare a language and viewport, use descriptive page titles and meta descriptions, provide image alternative text, use semantic landmarks, associate labels with form controls, expose the menu state through `aria-expanded`, and display form feedback using an accessible status region. CSS and JavaScript are stored in separate files and reused across all pages. The contact form is explicitly described as a demo rather than a live messaging service.

## 9. Testing plan and results to record
I Run the pages in a current browser and complete these checks before submission:----pass
1. I ALSO Verify all five HTML files open.----pass
2. I Follow every navigation link from each page.-----pass
3. The responsive layouts is at approximately 1440px, 768px and 390px widths.---pass
4. I Open/close the mobile navigation and verify `aria-expanded` changes.---pass
5. And i also Try submitting an empty contact form; browser validation prevents the submission.---pass
6.I Complete the form; a demo confirmation appears and fields reset later.----pass
7. I Also try Ticking checklist items on the trip-planning page.-----pass

## 12. Conclusion
The Explore Sierra Leone website demonstrates a five-page tourism information website built with HTML5, CSS3 and JavaScript. Its consistent navigation, destination content, planning checklist, contact form demonstration and responsive layout provide a foundation that could be expanded with verified tourism data, local photography, maps, live booking information and a secure server-side contact service.

## 13. References
- HTML Living Standard: https://html.spec.whatwg.org/
- MDN Web Docs (HTML, CSS and JavaScript): https://developer.mozilla.org/
- GitHub Docs: https://docs.github.com/


## Alignment with Assignment 1 wireframe
The updated website uses a clean black-and-white visual style, compact header, simple navigation, bordered cards, minimal buttons and responsive layouts to reflect the submitted Explore Sierra Leone wireframe. The five key views are Home, Destinations, Services (experiences page), About (trip-planning page), and Contact. The Search navigation link opens the destinations page where visitors can browse destinations.
