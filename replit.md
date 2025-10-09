# Static HTML Redirect Page

## Overview
This is a simple static HTML website that serves a redirect page. The page uses JavaScript to decode a base64 hash parameter and redirect to an external URL.

## Project Setup
- **Language**: Python 3.11
- **Server**: Simple Python HTTP server
- **Port**: 5000 (frontend)
- **Host**: 0.0.0.0

## Architecture
- `index.html` - Main HTML page with redirect logic
- `server.py` - Python HTTP server configured for Replit environment with cache control headers

## Recent Changes
- [Oct 9, 2025] Initial project import and setup
- Configured Python HTTP server to serve static content on port 5000
- Added cache control headers for Replit's iframe proxy
- Set up deployment configuration for autoscale

## Deployment
- Configured for autoscale deployment
- Production command: `python3 server.py`
