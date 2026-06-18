# Inner Space — Website Files

This folder contains your complete website: 6 pages, styling, and a tiny bit of interactive code. Here's everything you need to know to view it, edit it, and put it online.

## 1. Preview it right now

Double-click `index.html`. It will open in your web browser (Chrome, Edge, Safari, etc.) and you can click through Home, About, Events, Blog, and Contact exactly as a visitor would. The Events page filter buttons and the mobile menu (resize your browser window narrow, or open on your phone) both work already.

## 2. What's in each file

- **index.html** — Landing page (your "Inner Space" intro text and photo)
- **about.html** — About page (your bio — currently placeholder text in [brackets])
- **events.html** — Classes, workshops, retreats (5 placeholder events)
- **blog.html** — Blog listing (6 placeholder posts)
- **blog-post.html** — A sample full blog post, showing how an article looks
- **contact.html** — Contact form and your details
- **css/styles.css** — All the colors, fonts, and layout (one file controls the whole look)
- **js/main.js** — Powers the mobile menu and the events filter buttons
- **images/hero.png** — Your reference image, used on the landing page

## 3. Editing text and content

Every page is a plain text file underneath. You can open any `.html` file in:
- **Notepad** (Windows) or **TextEdit** (Mac, in plain-text mode), or
- a free editor like **VS Code** (a bit more pleasant to work in)

Find the sentence you want to change, edit it, save the file, and refresh your browser to see the result. Anything inside `[square brackets]` (in `about.html`, `events.html`, `contact.html`) is placeholder text written for you to replace — your name, bio, real event dates, email, and phone number.

**Tip:** Use your editor's "Find" (Ctrl+F / Cmd+F) to search for text like `[Your Name]` or `hello@innerspace.example` so you can replace it everywhere it appears (it's repeated in the footer of every page).

## 4. Adding your own photos

Right now, photo spots (the portrait on the About page, the blog thumbnails) are soft gradient placeholders with a glowing dot — intentional, so the site looks finished even before you add real photos.

To add a photo:
1. Put your image file (e.g. `me.jpg`) into the `images` folder.
2. In the HTML, find the placeholder `<div class="portrait">...</div>` (in `about.html`) and replace it with:
   ```html
   <img src="images/me.jpg" alt="A short description of the photo" style="border-radius:4px; width:100%; aspect-ratio:4/5; object-fit:cover;" />
   ```

## 5. Making the contact form actually work

The contact form on `contact.html` doesn't send anywhere yet — it needs a one-time, free setup:
1. Go to **formspree.io** and sign up free with your email.
2. Create a new form and copy the link it gives you (looks like `https://formspree.io/f/abcd1234`).
3. Open `contact.html`, find `https://formspree.io/f/REPLACE_WITH_YOUR_FORM_ID`, and paste your real link in its place.

After that, any message someone sends through the form will land in your email inbox.

## 6. Putting the site online (free options)

The simplest free option is **Netlify Drop**:
1. Go to **app.netlify.com/drop**
2. Drag this entire `inner-space` folder onto the page
3. You'll get a live link in seconds (you can later connect your own domain name, like `innerspace.com`, in Netlify's settings for a small yearly fee from a domain registrar)

## 7. Things you may want to do next

- Replace the 5 placeholder events on `events.html` with your real class schedule
- Replace the 6 placeholder blog posts (or remove some — even 1–2 real posts is fine to start)
- Add your real social media links in the footer (currently `#` placeholders)
- Update the phone number, email, and address (search for `innerspace.example`, `+91 00000 00000`, and `Hubballi`)

If anything feels confusing or you'd like help with a specific change, just ask — and feel free to describe what you want in plain language; you don't need to know any code terms.
