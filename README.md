# IntimateContentPlatform

A modern platform for intimate content featuring a brutalist aesthetic and advanced security resources.

## 🌟 Key Features

### 📱 Implemented Pages
- **Main Page**: Landing page with brutalist design and rose palette
- **Authentication**: Consistent Login and Signup styles
- **Feed**: Content viewing with interactions
- **Chat**: Real-time messaging system
- **Match**: Romantic video calls
- **Random**: Random chat with users
- **Profile**: User account management
- **404**: Custom error page

### 🎨 Design System
- **Brutalist Style**: Aggressive design with geometric shapes
- **Rose Palette**: 9 consistent rose tones throughout the application
- **Thematic Shapes**: Hearts, cupids, rings, infinity symbols
- **Animations**: Heartbeat, shake, float, pulse, and more
- **Responsive**: Adaptable for desktop and mobile

### 🔒 Security Features

#### Content Protection
- **Anti-Screenshot**: Limited screenshot capture protection
- **Watermark**: Invisible watermarking for traceability
- **Selection Block**: Text selection prevention
- **Image Protection**: Drag & drop disabling

#### System Blocks
- **DevTools Detection**: Developer tools detection
- **Keyboard Shortcuts**: Blocking F12, Ctrl+U, Ctrl+S, etc.
- **Context Menu**: Disabling right-click context menu
- **Print Screen**: Blocking Print Screen key

#### Security Headers
- **X-Frame-Options**: DENY - Prevents embedding
- **X-Content-Type-Options**: nosniff - Prevents MIME sniffing
- **X-XSS-Protection**: XSS protection
- **Referrer-Policy**: no-referrer - Reference privacy
- **robots.txt**: noindex, nofollow - No indexing

#### Additional Protections
- **Viewport Lock**: Manual zoom disabling
- **Visibility API**: Content blur when tab is inactive
- **Console Warnings**: Console warning messages
- **Auto-removal**: Automatic removal of warning overlays

### 🚀 Technologies

- **Next.js 14**: React Framework with App Router
- **TypeScript**: Static typing
- **Tailwind CSS**: Utility-first styling
- **Styled JSX**: CSS-in-JS for specific components
- **Lucide React**: Modern icons
- **Radix UI**: Accessible components
- **WebSocket**: Real-time communication (hooks prepared)

### 🎯 Rose Color Palette

css
:root {
  --misty-rose: #fadde1;
  --orchid-pink: #ffc4d6;
  --carnation-pink: #ffa6c1;
  --tickle-me-pink: #ff87ab;
  --french-rose: #ff5d8f;
  --bakermiller-pink: #ff97b7;
  --carnation-pink-2: #ffacc5;
  --pink: #ffcad4;
  --cherry-blossom-pink: #f4acb7;
}


### 🛡️ Security Architecture

#### SecurityProvider
Global component wrapping the entire application that implements:
- Keyboard and mouse event listeners
- DevTools detection
- Automatic watermarks
- Protection styles

#### Automatic Protection
The platform uses client-side mechanisms to deter unauthorized content capture and system inspection, ensuring a secure environment for users.

## Getting Started

First, run the development server:

bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev


Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

