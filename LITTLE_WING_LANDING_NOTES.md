# Little Wing Junior League Landing Page

## Files Created
- `/src/pages/little-wing-junior-league.astro` - Complete promotional landing page

## Assets Required
Add these images to `/public/` directory:
- `little-wing-logo.png` - Little Wing Pizzeria logo (provided separately)
- `ormeau-logo.png` - Already exists in `/public/ormeau-logo.png`

## Links to Update
Replace these placeholders in the `.astro` file:
- `SIGNUP_URL` (line ~280) - Replace with actual registration form URL
- `https://littlewingpizzeria.com` (line ~340) - Verify Little Wing's actual website URL

## Features Implemented
- ✅ Fully responsive design (mobile-first approach)
- ✅ Semantic HTML5 structure
- ✅ Matches existing Ormeau site styling (dark theme, primary red accents)
- ✅ All required sections with proper anchor IDs (#register, #contact)
- ✅ Quick facts strip with 6 cards
- ✅ Schedule timeline with 4 date cards
- ✅ FAQ section with all specified questions
- ✅ Smooth scroll navigation
- ✅ Hover states and micro-interactions
- ✅ Powder blue accent section for sponsor (Little Wing branding nod)
- ✅ Clean, scannable mobile layout

## Navigation
The page will be available at: `http://localhost:4040/little-wing-junior-league`

## Testing
- Test responsive behavior on mobile/tablet/desktop
- Verify all anchor links work smoothly
- Check logo placement and sizing
- Test form link when SIGNUP_URL is updated

## Notes
- Uses existing Ormeau design system (colors, fonts, spacing)
- Lightweight JavaScript only for smooth scrolling and animations
- No external dependencies beyond existing site assets
- Accessible semantic markup with proper heading hierarchy
