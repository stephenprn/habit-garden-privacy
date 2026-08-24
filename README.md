# Privacy policies

GitHub Pages, no build step, no Jekyll. Two policies, because there are two
listings on Google Play and they describe different apps.

| Path | Listing | Package |
| --- | --- | --- |
| [`/`](https://stephenprn.github.io/habit-garden-privacy/) | Habit Garden | `com.stephenprn.habitgarden` |
| [`/bonsai/`](https://stephenprn.github.io/habit-garden-privacy/bonsai/) | Bonsai | `com.stephenprn.bonsai` |

**Do not collapse them into one page while both listings are published.** They
are not the same document. Habit Garden's says "there is no export, no backup
and no import feature", which is true of that app and false of Bonsai; Bonsai's
describes the archive, the CSV, the poster and the two outbound links, and
enumerates six Android permissions where Habit Garden's enumerates five. A
listing whose policy describes features the app does not have is worse than no
policy, and Play requires the policy to stay live for as long as the listing
does.

Once Habit Garden is unpublished, `/` may be retired or made a redirect. Not
before.

## Editing

`bonsai/index.html` is a **deployed copy**. Its source of truth is
`docs/store/listing/07-privacy-policy.html` in the app repository, where it sits
beside the `.md` that records why each factual claim is worded the way it is and
what in the build it depends on. Edit it there, copy the file here, and the
hosted policy cannot drift from the one the release is checked against.

Both pages are fully self-contained — no external fonts, stylesheets, scripts,
images or trackers. That is deliberate and must stay true: a privacy policy that
loads a third-party font is a bad joke. The single `https://` reference on each
page is a hyperlink to Google's own policy that a reader may click, not a
resource the page fetches.

## What Play requires of the URL

Publicly reachable over HTTPS, no login, not a PDF, not an editable document
(Notion pages and shared Google Docs have both been rejected), and live for as
long as the listing is.
