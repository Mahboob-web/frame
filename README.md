# Bano Qabil Gujrat Graduation Photo Frame

A static, mobile-friendly photo frame page. Students choose a photo, drag to position it, adjust zoom, and download a PNG. The photo is processed locally in the browser; it is not uploaded to a server.

## Deploy on Vercel (beginner-friendly)

1. Sign in to https://vercel.com/.
2. Create a new GitHub repository, for example `banoqabil-graduation-frame`.
3. Upload `index.html`, `vercel.json`, and the `public` folder (which contains `frame.png`) to the repository root.
4. In Vercel, choose **Add New → Project**, import that repository, and deploy it as a static site. No build command is needed; use `./` as the output directory if asked.
5. Vercel will provide a public URL. Send that link to students on WhatsApp.

Important: keep `index.html`, `vercel.json`, and the `public` folder at the repository root. Do not upload only the HTML file, because the frame image is in `public/frame.png`.
