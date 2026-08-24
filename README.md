Custom Attendance Tracker README
Roll Call — Attendance Ledger
Your attendance, kept honest.
Roll Call is a lightweight, installable web app for tracking subject-wise class attendance — built for students who need to hit an attendance percentage target (75%, 80%, whatever your college demands) and want to know, at a glance, how many classes they can afford to skip or need to attend to get back on track.
Why this exists
I use an iPhone. When I went looking for a simple attendance tracker on the App Store, here's what I found: almost nothing free, most "attendance calculator" apps buried behind subscriptions or one-time paywalls, and the free ones were bloated, ad-heavy, or just didn't track what I actually needed — per-subject history, a target percentage, and a straight answer to "can I skip today or not."
Android has a healthy ecosystem of these apps. iOS doesn't, at least not for free. Rather than pay for something this simple, or settle for an app cluttered with features I didn't want, I decided to just build the tool myself.
Since I didn't want to deal with the App Store (developer account, review process, TestFlight just to use my own app), I built Roll Call as a installable web app instead — add it to your Home Screen from Safari and it behaves like a native app: full-screen, no browser chrome, works offline-first. No App Store, no subscription, no ads, just a tool that does the one thing I needed.
Features
Daily marking — mark each subject Present or Absent for any date, not just today
Per-subject targets — set your own attendance goal per subject (defaults to 75%)
Smart advice — for every subject, see exactly how many more classes you can miss (or need to attend) to stay on target
History — tap any subject's stamp to see and edit its full attendance log
Insights tab — overall present/absent donut chart, per-subject comparison bars, a 14-day activity heatstrip, and streak tracking
Backup/restore — export your data as JSON and import it back, so you're never locked in
Home Screen install — add-to-home-screen prompt so it runs like a native iOS app
No account, no ads, no tracking — your data stays on your device
Tech
Single-file HTML/CSS/JS. No build step, no framework, no backend. Data is persisted through a simple key-value storage layer (no localStorage dependency issues on iOS Safari's installed-PWA mode).
Installing on iOS
Open the app link in Safari
Tap the Share icon
Choose Add to Home Screen
That's it — it now opens full-screen like any other app.
Status
This is a personal tool I built to solve my own problem, shared in case it's useful to anyone else stuck in the same spot. It's not trying to be a polished commercial product — just a straightforward tracker that does the job the App Store wasn't offering for free.
Still a work in progress. It's functional and I use it myself, but it's not perfect yet — expect rough edges, missing features, and things that'll change as I keep iterating. Feedback and issues are welcome.
License
MIT
