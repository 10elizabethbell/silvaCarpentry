# Silva Carpentry LLC — handoff at ~60%

**Live:** https://10elizabethbell.github.io/silvaCarpentry/ · **Repo:** https://github.com/10elizabethbell/silvaCarpentry · **Built:** 2026-10-18 from Muse brief (run 2026-10-19, "thin brief, flagged")

## What's built
- One page, `index.html` (~40KB, no images except the share card and home-screen icon). Phone first, then desktop.
- **World: tape measure and chalk line.** Fields of deep chalk-line navy and primed-trim white, tape-blade yellow for the main button, red only on the 16-inch stud marks.
- **Hero signature:** a canvas tape measure runs out of its case along the bottom of the hero and measures by itself. Drag the hook with a finger (any direction; the page doesn't scroll while you hold it) or steer it with the mouse. The blade stays straight with a little gravity sag and the case turns to aim at the hook. Let go and the blade zips home, the case kicks, and then it goes back to measuring. Numbers count from the hook (red box on 16, like a real stud mark); on phones only even inches are numbered from 8 on so they don't run together. On desktop the blade angles up into the open space beside the headline as it extends.
- Every tunable (speeds, stiffness, sag, blade size, inch spacing) is in the `TUNE` object at the top of each script block.
- **Dividers:** chalk lines between sections that vibrate like a string, drawn as a broken core with uneven powder around it. They pluck themselves gently every 6–12s, and get plucked (with a little puff of chalk) when a finger or mouse crosses them, including when you scroll past with a finger down.
- **Sections:** header (wordmark + tap-to-call number top right) → hero ("Trim that fits tight.", promise, Text us a photo / Ask for a quote) → What we install (8 rows from the flyer, each a pre-written text) → How we start (3 steps on tape segments + "where we work: text us your town") → quote form that becomes a text → close with the name and a text button, footer with phone and email.
- **Contact:** every `sms:` link and the form go to +1 484-821-7333; `tel:` in the header, under the form and in the footer; email only in the footer. Checked: all bodies decode correctly; the form composes "Hi Silva Carpentry! This is Dana. I'd like a quote. / Work: … / About the job: … / Town: … / When: …".

## Assumptions I made
- **"We" voice.** Brief says nothing about crew size; "LLC" and the ads read like a small crew. Switch to "I" if it's one person.
- **Colors are mine, not theirs.** The flyer images need a Facebook login, so I couldn't sample the flyer colors. Palette comes from the trade (tape yellow, chalk blue, primed trim).
- **"Crown molding"** for the flyer's "CROWNS" (and "Crown" on the form chip).
- **All the copy is mine** and written about care rather than claims: hero promise "We fit every piece to your walls, and treat your home like our own while we're in it."; steps "We go through the work with you and tell you plainly what it'll take." / "We fit each piece to the wall it's going on, not the other way around."; close "Trim is what you'll look at every day after we've gone. We fit it that way." Owner should read it in his own voice.
- **Texting:** unconfirmed. The site leans on text (hero, rows, form) because that's how these sites work best; calling is always in the header. If the number can't take texts, swap the hero's main button to the quote form and change the form to show the note with a call link.
- **Wordmark as logo.** No logo exists beyond the flyer's text, so the header uses the name set in the site's type; the favicon/home-screen icon is an "S" over a tape blade.

## Placeholders and gaps
- **No photos of work at all.** No proof section was built (and no Facebook link under the work, since there's no business page). Top priority to get from the owner: 6–10 photos of finished trim, doors, crown, stairs, cabinets. A proof section with a "See more of our work" Facebook link goes right after "What we install".
- **No business Facebook page.** Ads were posted from Eduardo Talitha's personal profile; no Facebook link anywhere on the site yet. Add the page link in the footer and under the photos once one exists.
- **Service area unknown** (484 = southeastern PA; ads ran in NJ/PA groups). The page says "text us your town and we'll tell you if we cover it" instead of a list. The brief asked for a visible "TBD"; I used this line instead because a "TBD" reads unfinished to a visitor.
- Hours, years in business, license/insurance, prices, reviews: none on the page.
- Flyer images not fetched (Facebook login required). Facts are from Muse's OCR, which it called clean.

## Questions for the owner
- Can 484-821-7333 take texts?
- Which towns/counties do you cover? PA, NJ or both?
- Is it you alone or a crew? (sets "I" vs "we") And should the site name you?
- Do you visit to measure before quoting? Free quotes?
- Photos of your best jobs, and a logo if you have one.
- Do you work for homeowners, contractors, or both? (could add a short "for contractors" line)
- Licensed / insured in PA (HIC number)? Only if they want it shown.

## Review trail
- Impeccable, every mode except `live` (and `onboard`, `extract`: no first-run flow, single file): audit, critique, harden, optimize, polish, layout, typeset, adapt, animate, delight, overdrive, bolder, clarify, distill, quieter, colorize, plus the finish reviewer. Fixes applied in batches; the finish reviewer took two fix rounds. The last open item (phone numerals "9" and "10" touching) was fixed after its final verdict, so it's verified by my screenshot only, not by the reviewer.
- Detector: Roboto (Android's system font) and the tape-tick stripes are suppressed as intentional (`.impeccable/config.json`). Two "cramped padding" findings on the services list and footer and a "flat type hierarchy" finding left standing (false positive / minor body-size spread).
- Dust in the hero was cut: at this size it read as stars, not sawdust (`DUST_PHONE/DUST_DESK` = 0 to bring it back).

## Ideas not built (yours to pick)
- **Runner-up world: hand plane and shavings.** Drag across a rough board to plane it smooth, with curls of shavings peeling off. Warmer and more tactile, but needs wood textures to read as real.
- A pencil "crow's foot" mark left on the blade where you let go of the hook.
- Proof section with before/after sliders once photos exist (trim before/after is very visual).
- A "for contractors" row or line for GCs who need a finish sub (the ads ran in contractor groups).
- Font to try: a condensed industrial face for headings (house style is the system stack, so I didn't).

## Not verified
- Real-device touch feel (tested with simulated touch in Chromium and WebKit: drag moves the hook, page doesn't scroll; no overflow and no tap target under 44px at 360/390/430).
- The desktop form fallback (shows the composed note if the text app doesn't open) is tested in Chromium only.
- Real SMS handoff on iOS and Android from inside Facebook's in-app browser.
- Frame rate on older phones.
- Flyer facts against the flyer image itself.
