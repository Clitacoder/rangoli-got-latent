# Rangoli Face-Off

Static site (no build step). Deploy: push this folder to GitHub and import it in Vercel
(Framework preset: Other), or run `npx vercel` inside the folder.

Roles (all on the same URL):
- Host:  /?role=host   (creates a 4-letter room code; shows Invite links)
- Team:  /?role=team&r=CODE
- Juror: /?role=jury&r=CODE

Sync uses PeerJS (WebRTC, free public broker). The host tab is the hub: keep it open.
Test on one computer without internet sync: add &local=1 to every link.
