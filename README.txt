JARVIS CROSS-DEVICE — FREE BUILD 2.0
=====================================

WHAT YOU GET
- Responsive Iron Man-inspired dashboard for Windows PC and Android phone.
- Tap-to-listen English speech commands (where browser speech recognition is supported).
- Spoken responses using browser text-to-speech.
- Basic commands: time, open YouTube, open Google Maps, open ChatGPT, identify, web search.
- PWA install support on HTTPS hosting.

IMPORTANT LIMITATIONS
This is a free starter assistant, not a full autonomous AI or an always-on wake-word assistant.
It does not include a private AI model/API, unlimited AI chat, arbitrary Android system settings control,
or unrestricted Windows desktop control. Speech recognition support varies by browser/device and may
use an online speech service. The mic only starts after the user presses Start Listening.
The same web app can be installed on both devices, but settings/history are not synced between them.

PART A — PUBLISH IT FREE USING GITHUB PAGES
1. On a PC, visit https://github.com and sign in or create an account.
2. Create a new PUBLIC repository named: jarvis-cross-device
3. Extract this ZIP on your PC.
4. Upload these four files from the extracted folder to the repository root:
   index.html, manifest.json, sw.js, icon.svg
   (README.txt is optional.)
5. Open the repository's Settings → Pages.
6. Under Build and deployment, choose "Deploy from a branch".
7. Choose branch "main" and folder "/ (root)", then Save.
8. Wait a minute or two. GitHub Pages will show the published HTTPS website address.
9. Open that address in Chrome or Edge on your PC and test it.

PART B — INSTALL ON WINDOWS PC
1. Open the published HTTPS address in Google Chrome or Microsoft Edge.
2. In Chrome, use the install icon in the address bar if shown, or menu ⋮ → Cast, save, and share / Save and share → Install page as app (wording varies).
   In Edge, use menu ⋯ → Apps → Install this site as an app.
3. Allow microphone permission when prompted.
4. Pin the installed app to the taskbar or Start menu if desired.

PART C — INSTALL ON SAMSUNG M34 5G
1. Open the exact same HTTPS address in Chrome.
2. Tap the three-dot menu.
3. Choose "Add to Home screen" or "Install app" (wording varies).
4. Confirm. JARVIS appears as an icon on the home screen.
5. Open it and allow microphone permission.
6. Tap START LISTENING and try "What time is it?" or "Open YouTube".

VOICE TROUBLESHOOTING
- Use an up-to-date Chrome or Edge browser.
- Confirm the site is opened using HTTPS, not a local file:// address.
- Allow microphone permission for the site.
- Android: Settings → Apps → Chrome → Permissions → Microphone → Allow while using.
- Windows: Settings → Privacy & security → Microphone; allow browser microphone access.
- If speech recognition is unsupported, use the command text box.
- Browser speech recognition can require internet and may stop when the app is backgrounded.

TEST COMMANDS
"What time is it?"
"Open YouTube"
"Open Google Maps"
"Open ChatGPT"
"Search for latest space news"
"Who are you?"

NEXT DEVELOPMENT STAGES
To add genuine AI conversation, a model/backend or AI service is needed; do not put private API keys inside public website files.
To add reliable cross-device memory, accounts and a database/backend are needed.
To control Android system features or Windows apps, use a separately installed native app with explicit permissions.
