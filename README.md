# kinspace
Navigating social anxiousness

KinSpace · app prototype
A working, clickable prototype of KinSpace, a care-continuity app for young adults (20–30) who feel anxious in social situations. It supports small, chosen social steps, relief in the moment, and reflection without judgement, on your own or alongside a therapist.

Built as part of a service design project (DP-2). It is a design prototype, not a medical service.

Run it
No build step and no dependencies. Open index.html in any modern browser.

What you can try
Flow	Screens
A · Onboarding	Welcome → promises → choose a route → therapist code (try KS4291) → goal → who it’s for → first step size
B · A session	Home → need help? → make choices (tension before) → in session (timer) → pocket mode → how did it go → reflect → feedback
C · Evening and progress	Night replay (3 cards) → track → patterns with reasons → goal ladder
D · Community	Area view → write a message → posted · mute or report
E · Help	Help → therapist connected → choose what to share → share preview → from your therapist → find help → urgent help
F · Me	Settings → privacy and data → reminders and quiet hours
The panel beside the phone lets you jump to any screen, or start again from onboarding.

Notes
Choices are saved in your browser’s localStorage only. Nothing is sent anywhere.
Pocket mode uses the Vibration API, which works on Android phones after a tap. On other devices it shows a breathing light instead.
Names, numbers and therapist details are fictional sample data.
KinSpace is a wellbeing concept, not an emergency service. In India, Tele-MANAS is free on 14416; in immediate danger, call 112.
Tech
A single HTML file: plain HTML, CSS and JavaScript, with the Inter Tight font from Google Fonts.
