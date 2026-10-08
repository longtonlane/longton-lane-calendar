# Longton Lane School — Parents' Calendar 2026–2027

A simple, unofficial parent-created school calendar website, hosted for free with GitHub Pages. Parents can subscribe to the school events on iPhone, Android, or other calendar apps.

## Files

- `index.html` — mobile-friendly website, subscription links and upcoming events.
- `Longton_Lane_School_2026-2027.ics` — calendar data (keep this exact filename unless you update `index.html`).

## Set up GitHub Pages

1. Create a **public** GitHub repository, for example `longton-lane-calendar`.
2. Upload `index.html`, this `README.md`, and `Longton_Lane_School_2026-2027.ics` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, `main`, and `/(root)`; save.
5. Once published, visit `https://YOUR-USERNAME.github.io/longton-lane-calendar/`.
6. Share that **webpage URL** with the parents' WhatsApp group.

The page calculates the subscription URL automatically from its own address, so there is no need to edit your username into the HTML.

## How parents subscribe

**iPhone:** Open the webpage on the iPhone and tap **Add to iPhone Calendar**. Approve the subscription when prompted. If that doesn't work, use **Settings → Apps → Calendar → Calendar Accounts → Add Account → Other → Add Subscribed Calendar**, then paste the HTTPS URL shown on the page (menus can vary by iOS version).

**Google Calendar / Android:** On a computer, open Google Calendar → **Other calendars** → **+** → **From URL**, and paste the HTTPS calendar URL displayed on the webpage. Google Calendar may take time to refresh subscribed calendars. The Google Calendar mobile app does not always offer the URL subscription setup option.

## Update events

Replace the `.ics` file in the repository with an updated file **using the same filename**. Subscribers will receive changes when their calendar apps refresh; timing depends on the app. Keep event UIDs stable when editing existing events to avoid duplicates.

## Privacy and notes

- The GitHub repository and GitHub Pages site are **public**. Do not include private pupil information.
- GitHub usernames and public commit metadata may be visible. Use a neutral account if you don't want your personal GitHub identity associated with the site.
- This is **not an official school calendar**. Refer to school notices for changes.
- The supplied source calendar appears to have an inconsistent year for World Book Day; check that entry against school communications.
- The website itself collects no user details and uses no tracking scripts.
