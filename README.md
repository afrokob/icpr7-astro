# ICPR7 2026 - Conference Website

Official website for the 7th International Conference on Practice Research, held in Singapore, July 7-9, 2026.

## Theme
Practice Research Without Borders: Inclusion and Change Across Sectors and Contexts

## Technology Stack
- **Framework**: Astro 4.x
- **Styling**: Tailwind CSS
- **Deployment**: Vercel
- **Font**: Inter (Google Fonts)

## Design Philosophy
This website follows a professional academic design approach with:
- Clean, minimalistic layout with ample whitespace
- Neutral color palette (grays, blues, whites) for professionalism
- Accessible design with WCAG 2.1 compliance
- Mobile-responsive design
- Fast loading with static site generation

## Development

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Getting Started
```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Project Structure
```
├── src/
│   ├── components/
│   │   ├── Nav.astro           # Main navigation with dropdown
│   │   ├── SpeakerCard.astro   # Speaker profile cards
│   │   ├── ImportantDates.astro # Conference dates section
│   │   └── Footer.astro        # Site footer
│   └── pages/
│       └── index.astro         # Homepage
├── public/                     # Static assets
├── astro.config.mjs           # Astro configuration
├── tailwind.config.mjs        # Tailwind configuration
└── package.json
```

## Accessibility Features
- Semantic HTML structure
- ARIA attributes for screen readers
- High color contrast ratios
- Keyboard navigation support
- Alt text for images
- Focus indicators

## Deployment
This site is configured for deployment on Vercel with static site generation for optimal performance.

## License
MIT