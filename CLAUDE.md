# Ocean Website

This is a website for marketing a mobile application called Ocean.

Ocean is a new dating app that I'm creating. It will be available for iOS and Android.

The name of the app is Ocean. The tagline for the app is "The AI-powered dating app".

## Current Implementation

The website has been built using Astro and is fully functional with the following structure:

### Pages
- **Home page** (`/src/pages/index.astro`) - Landing page with hero section, feature highlights, and coming soon CTAs
- **About page** (`/src/pages/about.astro`) - Detailed information about Ocean's mission and AI-powered features
- **Blog page** (`/src/pages/blog.astro`) - Blog directory with coming soon message and content preview
- **Privacy Policy** (`/src/pages/privacy.astro`) - Comprehensive privacy policy covering data collection, usage, and user rights
- **Terms of Service** (`/src/pages/terms.astro`) - Legal terms including user conduct, eligibility, and service guidelines

### Design & Branding
- **Primary color**: #34B5B3 (ocean teal) - used as page background
- **Accent color**: #EDFBFA (light mint) - used for text and button backgrounds
- **Supporting colors**: #2a9290 (darker teal) for headers/footers, #f0fcfc (lighter mint) for hover states
- **Typography**: System UI font stack with consistent sizing and spacing
- **Logos**: 
  - `ocean_logo.png` - used on home page hero (120px height)
  - `ocean_wordmark.png` - used in header navigation (40px height)
  - Both stored in `/public/` directory

### Features
- Responsive design with mobile-first approach
- Consistent navigation header with Ocean wordmark
- Footer with links and copyright
- Hero section with app download CTAs (placeholders)
- Feature highlights showcasing AI-powered matching
- "Coming Soon" section for iOS/Android notifications
- Professional legal pages with proper formatting

### Technical Details
- Built with Astro 5.11.0
- Global CSS with CSS custom properties for theming
- Mobile-responsive layout with flexbox and grid
- Semantic HTML structure
- Accessible navigation and content hierarchy

### Development Commands
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
