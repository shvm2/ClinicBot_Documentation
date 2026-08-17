# ClinicBot Case Study Website

Static, Vercel-friendly landing page for the ClinicBot project. It includes:

- Project/case-study homepage
- Responsive WhatsApp conversation mockup based on the actual current ClinicBot flow
- Architecture diagram
- Engineering highlights
- Demo placeholder for a 45–60 second recording
- Private-source-code positioning
- Dedicated `/privacy.html` page using the supplied Privacy Policy copy

## Deploy to Vercel

1. Put this folder in a Git repository (a separate public website repo is fine).
2. Import the repo into Vercel.
3. Framework preset: **Other** / static.
4. Build command: leave empty.
5. Output directory: leave empty (project root).
6. Deploy.

You can also place the files directly under your existing portfolio repo and use a path such as `/clinicbot`.

## Add the real demo video

Record the ClinicBot flow using your Meta WhatsApp test number and save the file as:

`assets/clinicbot-demo.mp4`

Then replace the demo placeholder in `index.html` with:

```html
<video controls playsinline preload="metadata" poster="assets/clinicbot-demo-poster.png">
  <source src="assets/clinicbot-demo.mp4" type="video/mp4">
</video>
```

## Suggested LinkedIn flow

- Feature the landing page URL.
- Publish a ClinicBot case-study post and feature that post too.
- Add ClinicBot under LinkedIn Projects with the landing page as the project URL.
- Keep the actual GitHub repository private.
