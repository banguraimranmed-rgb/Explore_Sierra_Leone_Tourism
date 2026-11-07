# Explore Sierra Leone — Responsive Tourism Website

## Project overview
A five-page responsive website promoting tourism destinations and experiences in Sierra Leone. Built with semantic HTML5, CSS3 and vanilla JavaScript for DCOMP 204 Web Design Assignment 2.

## Pages
1. `index.html` — Home page and featured destinations.
2. `destinations.html` — Destination guide: River No. 2 Beach, Tiwai Island, Banana Islands and Freetown.
3. `experiences.html` — Beach, nature, culture, heritage, island and community tourism.
4. `plan.html` — Travel checklist and illustrative three-day itinerary.
5. `contact.html` — Accessible contact form with front-end validation/demo confirmation.

## How to run
1. Download and extract the ZIP folder.
2. Open `index.html` in a modern browser, or use Visual Studio Code with the Live Server extension.
3. Internet access is needed for Google Fonts and the remote Unsplash photos. The layout and text remain available without those services.

## Responsive design
CSS media queries target desktop/tablet widths at 850px and mobile widths at 560px. The mobile navigation becomes a toggle menu, card grids collapse and the two-column layouts stack vertically.

## Testing checklist
- [ ] Open all five pages and click each navigation link.
- [ ] Test layout at desktop width, tablet width and mobile width.
- [ ] Open the mobile menu and confirm it opens/closes.
- [ ] Submit the contact form with missing fields and confirm browser validation.
- [ ] Submit a completed contact form and confirm demo status appears.
- [ ] Test the trip checklist by checking items.
- [ ] Check image alt text, heading hierarchy, focus states and readable contrast.

## Important notes
- The contact form is a front-end demonstration only; it does not transmit or store messages.
- Destination information is educational. Visitors should confirm current travel arrangements, conditions and costs with reliable local sources.
- Remote photos are sourced from Unsplash URLs and require internet access. Replace with properly licensed local images before public launch.

## GitHub repository setup
Create a new GitHub repository named `explore-sierra-leone-tourism`. From this folder run:

```bash
git init
git add .
git commit -m "Build responsive Sierra Leone tourism website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/explore-sierra-leone-tourism.git
git push -u origin main
```
Replace `YOUR-USERNAME` with your GitHub username. Do not submit a made-up repository URL; create the repository and push the source first.
