https://niraj-patil.github.io/Tic-Tac-Toe/

# Neon Arena Tic-Tac-Toe

A responsive browser game with:
- Local 2-player mode
- Computer opponent with Easy, Medium and Hard levels
- Online host/join rooms using PeerJS
- Score tracking, restart, mobile-friendly layout
- PWA manifest and service worker for installation/offline shell caching

## Run it now
Open `index.html` in a modern browser. Local modes work without a server. Online mode needs internet access because PeerJS is loaded from a CDN and uses its public signaling service.

## Install on a phone
For the install prompt and service worker, serve this folder over HTTPS (for example, publish it on a static hosting provider). Open the HTTPS site in Chrome on Android and choose **Install app** or **Add to Home screen**. No Play Store developer registration is needed for this web-app route.

## Important online note
Online mode is peer-to-peer after signaling and works best when both players can reach each other. Some networks/firewalls may block peer connections. The included version does not require you to operate your own server, but it relies on the public PeerJS signaling service.

## Play Store
This is a web app/PWA, not an Android APK or AAB. Publishing a native Play Store app would require packaging/testing it for Android and a Google Play developer account.
