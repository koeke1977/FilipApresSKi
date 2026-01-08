# FilipApresSKi

HTML landing page for exchanging après-ski pictures from Dropbox to users.

## Features

- 🎿 Modern, responsive landing page design
- 📦 Dropbox integration for photo sharing
- 🖼️ Gallery view for browsing shared photos
- 🔐 Secure OAuth2 authentication
- 📱 Mobile-friendly responsive design

## Getting Started

1. Open `index.html` in your web browser to view the landing page
2. To enable full Dropbox functionality:
   - Create a Dropbox app at [dropbox.com/developers/apps](https://www.dropbox.com/developers/apps)
   - Get your App Key
   - Replace `YOUR_APP_KEY` in the `index.html` JavaScript section
   - Set the redirect URI to match your domain (e.g., `https://yourdomain.com/callback`)

## Files

- `index.html` - Main landing page with Dropbox integration
- `callback.html` - OAuth callback handler for Dropbox authentication

## Demo Mode

The page works in demo mode without Dropbox credentials, showing the UI and functionality structure. Connect a real Dropbox app to enable full features.

## Usage

Simply open `index.html` in a web browser. Users can:
- View the landing page with après-ski theme
- Connect their Dropbox account (when configured)
- Upload and share their après-ski photos
- Browse photos shared by others 
