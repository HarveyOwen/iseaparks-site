# iseaparks.com

The website for the I Sea Parks iPhone app: a landing page, the privacy policy (`/privacy/`) and
support (`/support/`). The app links to both URLs, so keep those paths.

Plain HTML and one stylesheet, no build step. GitHub Pages serves `main` from the repo root, so
committing a change to `main` publishes it within a minute or two. `CNAME` holds the custom domain
and `.nojekyll` turns off Jekyll processing; leave both in place.

When you change the privacy policy, update its "Effective" date.
