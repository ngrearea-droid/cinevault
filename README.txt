CINEVAULT V4

This version fixes the add flow, date default, swipeable star rating, automatic TMDB genres, original-language title display, poster selection/upload, and adds PWA files.

TMDB token: save your API Read Access Token in localStorage under the key cinevault_tmdb_token (do not publish the token).

Important: a PWA cannot be installed from a local file:// page in iPhone Safari. Deploy these files to an HTTPS URL (for example GitHub Pages), then open that URL in Safari and use Share -> Add to Home Screen.

The frontend stores records in localStorage. For a public deployment, do not expose the TMDB token in client-side code; use a server-side proxy.
