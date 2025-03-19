# Our Italian Journey

A bilingual (English and Slovenian) responsive React/Vite application for Italian travel destinations, featuring a three-region navigation system, Italian flag-inspired design, and simplified destination browsing.

## Features

- Responsive design optimized for mobile, tablet, and desktop
- Bilingual content management (English and Slovenian)
- Interactive Italy map with region-based navigation
- Content management through Netlify CMS
- Blog section with travel stories
- Destination guide with detailed information about Italian regions

## Development

### Prerequisites

- Node.js 18+
- npm 9+

### Setup

1. Clone the repository
2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

## Deployment to Netlify

### Manual Deployment

1. Build the project:

```bash
npm run build
```

2. Upload the `dist` directory to Netlify through their web interface

### Git-based Deployment

1. Connect your GitHub repository to Netlify
2. Configure the build settings:
   - Build command: `npm run build`
   - Publish directory: `dist/public`
   - Node.js version: 18

3. Enable Netlify Identity for CMS access:
   - Go to "Identity" tab in Netlify dashboard
   - Enable Identity service
   - Configure registration preferences
   - Set up the Identity service
   - Enable Git Gateway

4. Access your CMS at `yoursite.netlify.app/admin/`

## Project Structure

- `client/` - Frontend React application
- `server/` - Backend Express API
- `content/` - Content managed by Netlify CMS
- `shared/` - Shared code between client and server

## Content Management

The website uses Netlify CMS for content management. Once deployed, you can access the CMS at `/admin` and manage:

- Blog posts (bilingual)
- Destinations (bilingual)
- Region information (bilingual)

## License

[MIT](LICENSE)
