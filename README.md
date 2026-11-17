# Job Search Log

A free job search log for formerly incarcerated individuals. It keeps a line for every job application, shows how many applications were made this week, flags follow-ups that are due, and prints a clean record that can be kept or shown to a parole officer or program if they ask for one. It runs entirely in the browser: no account, no server, and nothing typed into it is sent anywhere.

Try it at https://olivercrocco.com/job-search-log/, or download `job-search-log.html` and open it in any browser. The single file works without the internet.

It was built for an employment skills course in a Louisiana reentry bridge program for people in their first year after release, and is part of the [Reentry Toolkit](https://olivercrocco.com/reentry/). Nothing in it is specific to Louisiana.

## What it does

- Records each application: date, employer, job, how the person applied, who they talked to, where it stands (applied, waiting to hear back, interview scheduled, offer, hired, not selected), a follow-up date, and notes.
- Shows applications this week, applications in all, and interviews scheduled, and lists the employers it is time to follow up with.
- When an interview is scheduled, makes a calendar file for that interview with reminders the day before and one hour before, to add to a phone.
- Prints the log as a one-page table.
- Offers "Keep my work on this device" for a person's own phone or computer. Otherwise nothing is stored, and work is kept with "Save my work."
- Includes "See an example," a "Try it with an example" walk-through with a made-up job search, and a button that reads each step aloud.

It states no rules about job search requirements. Programs using it should add their own guidance on what their officers or staff ask for.

## Files

- `job-search-log.html`: the whole tool in one file. This is the source of truth.
- `build-web.mjs`: builds `web/` for sites whose Content-Security-Policy blocks inline scripts. Run `node build-web.mjs` after editing.
- `web/`: the built web version.

## License

MIT. See `LICENSE`.

Built for formerly incarcerated individuals and the programs that support them, by Oliver S. Crocco, Louisiana State University.
