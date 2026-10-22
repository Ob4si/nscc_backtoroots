# NSCC 2026 · Back to the Roots

Website prototype for the **Nigerian Students Coalition Conference (NSCC) 2026**, hosted by the Nigerian Students Association at San José State University with Stanford.

Theme: **Back to the Roots: An Ancestral Tribute**, celebrating Nigerian heritage through village life, cultural traditions and 1960s highlife.

## What's in it

- **Opening:** tribal leaves frame both sides of the screen and part as you scroll, revealing the NSCC logo (placeholder) in the center.
- **Theme meaning:** the theme summary lights up word by word, followed by four pillars.
- **Drums:** playable gángan, ụdụ and ekwe drums synthesized with the Web Audio API, a "Play a rhythm" loop, and talking-drum waveforms that react to scroll speed.
- **Village strip:** a pinned section that scrolls sideways through 1960s village scenes.
- **Highlife:** a vinyl record that spins as you scroll, plus an equalizer.
- **Tickets:** Early Bird, General Admission and School Delegate tiers with quantity pickers and a running total. Prices are planning numbers. Checkout is a placeholder.

## Run it

It's one self-contained file with no build step. Open `index.html` in a browser.

## Publish with GitHub Pages

In the repo, go to **Settings → Pages**, set the source to **Deploy from a branch**, pick `main` and `/ (root)`, and save. The site will be live at `https://<username>.github.io/<repo-name>/`.

## To do

- Replace the NSCC placeholder with the real logo
- Add photos or illustrations to the village cards
- Lock in ticket prices and delegate perks
- Connect checkout to a payment provider (Stripe, Eventbrite, etc.)
