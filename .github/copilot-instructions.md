# Golf Club Management System
VGCMS serves as a central platform where members can:
- Access club and tournament information
- View event calendars
- Follow competition results
- Manage and track match play tournaments
- Browse historical achievements and winners
- Maintain member/player data

## Code Style
- HTML: Use semantic tags (section, header, nav, article)
- CSS: Follow BEM naming (e.g., `.section-title`, `.card-header`)
- Use CSS custom properties defined in `:root` for colors and spacing

## Architecture
- Responsive grid layouts using CSS Grid
- Component-based card design (`.result-card`, `.info-card`, `.tour-card`)
- Smooth transitions and animations for better UX

## Build and Test
- No build step required—static HTML/CSS files
- Test by opening `Index.html` in a browser
- Verify styling at 768px breakpoint for mobile

## Media
Use content of the Media folder for images, videos, and other assets 

## Structure 
├── Information
├── Kalender
├── Resultater
├── Hulspil
├── Hall of Fame
├── Stamdata



## Conventions
- All dates use Danish format (dd. month YYYY)
- Golf-themed colors: forest green (#1f4d2e), fairway green (#4e8b4a), sunshine gold (#f4c542)
- Content sections use smooth scroll behavior and staggered animations