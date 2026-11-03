# Ghats / Fieldnotes

Live: https://aditya2375.github.io/ghats-fieldnotes/

An illustrated Western Ghats journal. Built-in stories, route numbers and photographs are samples, not evidence of real treks or navigation/safety advice.

`npm install` then `npm run dev`. `npm run build -- --base=/ghats-fieldnotes/` builds for the original Pages path. Fonts and images are self-hosted.

## Your notes

New notes default to local drafts in this browser. Export each draft as JSON from its story page for backup. Restricted/full storage retains the draft only in this tab and displays a warning. No local drafts are sent to the server.

Checking Share publicly sends that note to the shared Supabase visitor journal. Anyone can read it. Do not include private information. The UI cannot edit or delete public notes; for help contact adityakulkarnicoding@gmail.com. The public endpoint/key is not a secret and does not itself prove row-level security or moderation. Server policy and retention require a separate backend audit. Public notes are unverified visitor content.

Remote reads are limited to100notes with validation,15s timeout and a1.5MB parsed-text limit. Public submissions are not retried automatically: a missing confirmation may still mean the server stored the note. Check Shared before resubmitting. Browser drafts validate shape, lengths and image position; invalid saved objects are ignored without executing markup. An unavailable shared journal leaves samples and local drafts usable.
