WEB 6 - AREND website (arend.llc), saved 2026-11-13

TO VIEW: double-click index.html (keep the img folder next to it).
"WEB_6.html" (sent separately) is the same site as ONE file with every image and
the home video built in, so it opens on its own with no img folder (about 47 MB).

TO PUBLISH ON GITHUB PAGES: unzip, then drag index.html and the img folder
(not the zip, not the "WEB 6" folder) into the top level of the repository.
Then submit a test message on the live Contact page and click the activation
link FormSubmit emails to info@arend.llc (check spam). After that, every
message comes through. Optional: swap the email in FORM_ENDPOINT for the
random alias FormSubmit sends, so the address isn't visible in the code.

TO KEEP WORKING IN A NEW CLAUDE CONVERSATION:
Attach this zip and say "continue working on the AREND WEB 6 site".
preview-source.html is the editable source used for the Claude artifact
(no doctype/html/head wrapper - the artifact adds it);
index.html is the same site wrapped as a standalone web page.
Single file, hash routing: #home #about #news #design #consulting #contact
#accessibility #privacy #cookies. News stories live in a JS "stories" array.

Changes since WEB 5:
- Home hero: looping 1080p video (img/home-hero.mp4, poster img/home-hero-poster.jpg),
  sized to the screen, same parallax and fade; pauses off screen, still frame for
  reduced motion
- Home: "Selected work / Thoughtfully Designed Spaces" and "Workflow automation"
  headers with grey subtext, intro text and links beside them removed; stat tiles
  removed from the Philosophy box; Philosophy label and About AREND link restyled
- Clicking the logo or the current page's link scrolls back to the top
- Image tiles: fix for grey hairlines at the rounded edges
- About: new hero photo (img/about-hero.jpg, Pascal Bullan / Unsplash);
  philosophy section split: "Our philosophy" centered on the left, dark folder
  box with 4 animated 3D tabs on the right (Who we are, What we do, How we work,
  Why we do it)
- Design: 7600 West Lane images reordered (plan, elevation, render, axon)
- Contact: working form (FormSubmit to info@arend.llc, spam trap, inline
  success/error messages); intro moved into the dark form box; hero-style Send
  button; email shown as plain text; contact details centered beside the form

Still to do:
- Review the copy in the 4 About tabs; "Why we do it" repeats the philosophy text
- Vaulted Portico article text still reads as "proposed / construction underway"
- PhD reviewer bio, consulting sample projects
- Mailing address on legal pages
- Cookie consent banner and skip-to-content link (described in the legal pages)
- Photographer credits for "Photo: Pexels" captions
