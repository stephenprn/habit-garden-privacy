# Privacy policy

GitHub Pages, no build step, no Jekyll. One page, one URL:

**https://stephenprn.github.io/habit-garden-privacy/**

It is the privacy policy for **Bonsai** (`com.stephenprn.bonsai`), and it is
also the URL on the **Habit Garden** listing (`com.stephenprn.habitgarden`),
which is still published while it is retired. One URL serving two listings is
why the page carries an *"If you are using Habit Garden"* section: without it
the page would describe an export, a spreadsheet and a poster that Habit Garden
does not have, and enumerate one permission it does not ask for. A listing whose
policy describes features its app lacks is worse than a stale one.

**Delete that section once Habit Garden is unpublished**, and nothing else needs
to change.

## Editing

`index.html` is a **deployed copy**. Its source of truth is
`docs/store/listing/07-privacy-policy.html` in the app repository, where it sits
beside the `.md` that records why each factual claim is worded the way it is and
which build fact it depends on. Edit it there, copy the file here, then re-add
the Habit Garden section — it is the one part of this page that is not in the
source file, because it is about hosting rather than about the app.

Two properties must survive any edit:

- **Self-contained.** No external fonts, stylesheets, scripts, images or
  trackers. A privacy policy that loads a third-party font is a bad joke. The
  single `https://` reference on the page is a hyperlink to Google's own policy
  that a reader may click, not a resource the page fetches.
- **No comments carrying notes.** An HTML comment is served with the file. This
  page previously shipped a `<!-- BEFORE PUBLISHING -->` block listing every
  placeholder and internal build fact, readable in view-source on a live legal
  document.

## What Play requires of the URL

Publicly reachable over HTTPS, no login, not a PDF, not an editable document
(Notion pages and shared Google Docs have both been rejected), and live for as
long as either listing is.
