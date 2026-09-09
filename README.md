# aura-privacy

The privacy policy for **Aura Migraine Diary**, and nothing else.

Published at <https://williamscott701.github.io/aura-privacy/> — the URL in the app's
`LegalLinks.privacy`, in App Store Connect → App Privacy, and on the paywall and Settings
screens that App Review opens.

## Why this is a separate repository

The app is in a private repository. GitHub Pages needs a public one on a free plan, and
publishing the app repository to serve a single page would also publish its `docs/`: the
keyword strategy, the revenue-model note and the subscription pricing. One extra
repository is cheaper than that.

There is deliberately no copy of this text in the app repository. Two copies of a legal
document is the same trap as two copies of a placeholder URL — the one somebody remembers
to edit is not necessarily the one that is served.

## Editing it

Edit `index.html` and push to `master`; the workflow redeploys. Change the effective date
at the top of the page with any substantive edit.

The page states that Aura has no account, no server, no analytics and no network calls,
and that its App Store privacy label reads "Data Not Collected". The same claim is on the
privacy screen of the app's introduction, on its privacy card in Settings, on the paywall, and in
its `PrivacyInfo.xcprivacy`. Anything that makes a network request falsifies all five at
once.
