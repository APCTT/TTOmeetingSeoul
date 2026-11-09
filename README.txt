TTO Network Seoul 2026 – Offline Web App

1. Upload the entire tto-guide folder to an HTTPS web server (e.g. your institutional website or static hosting).
2. Share the resulting index.html URL with participants.
3. Participants open it once while online, wait for 'Offline guide ready', and can add it to their phone home screen.
4. Essential pages, addresses, and QR codes work offline. NAVER Map and taxi booking links need internet.
5. To update content after publication, edit files and increment CACHE in sw.js (e.g. tto-seoul-v2), then redeploy.

Items to confirm before circulation:
- STEPI contact and technical visit pickup time/location.
- Hotel allocation for each participant.
- Day 1 registration time.

No organizer logos are included because official artwork was not provided.

Weather: static forecast snapshot checked 9 Nov 2026, cached offline; live forecast link needs internet.

Weather: Open-Meteo forecast for 17-18 November 2026, refreshed when online every 3 hours and saved in localStorage for offline use. If the API is unavailable or both dates are not in forecast range, cached data is shown; otherwise no invented forecast is displayed.

Version 4: Added separate k.ride App Store and Google Play download QR codes and links; service-worker cache updated.

Version 5 (9 Nov 2026): Hotel-specific airport bus guidance: Riviera 6006 / Cheongdam Xi; Aiden 6703 / Nonhyeon-dong (Sunshine Hotel). Official operator route-map/timetable links, stop NAVER Map links, fare and terminal boarding bays. Cache version v5.
