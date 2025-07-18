```
# Paulo C. M. Lyra Jr. — Personal Webpage

This repository contains the source code and assets for **Paulo C. M. Lyra Jr.**’s professional and scientific personal website. It showcases Dr. Lyra’s background, CV, publications, projects, and contact information in a clean, modern, and responsive design.

---

## 🚀 Features

- **Minimalist, professional design** using a mature color palette (soft backgrounds, deep text, vibrant accent) and the Inter font.
- **Single-page homepage** (`index.html`) with sticky navigation to About, Experience, Publications, and Contact sections.
- **Dedicated pages** for:
  - **Curriculum Vitae** (`cv.html`) — detailed education, positions, skills, and certifications.
  - **Publications** (`published.html`) — metrics summary and a list of peer-reviewed articles (14 entries, up to June 2025).
  - **Projects** (`projects.html`) — overview of research and software initiatives.
  - **Contact** (`contact.html`) — email, phone, ORCID, GitHub links.
- **Responsive layout** leveraging Bootstrap on secondary pages and custom CSS on the homepage.
- **Easy updates**: content is static HTML; simply edit the `.html` files or update the CV PDF (`CV_Current.pdf`) to reflect new information.

---

## 🎨 Styles & Assets

- **CSS**:
  - **Homepage**: custom minimalist styles in `<style>` tags.
  - **Secondary pages**: Bootstrap 4.6 for grid, typography, buttons.
- **Fonts & Icons**:
  - Google Fonts — Inter (weights 300, 400, 600).
  - Favicon and logo in `figures/hiclipart.com.png`.
- **Scripts**:
  - jQuery and Bootstrap Bundle for navigation collapse and interactivity.

---

## 📂 Repository Structure

```plaintext
├── css/
│   └── bootstrap.min.css
├── figures/
│   └── hiclipart.com.png      # favicon & logo
├── index.html                 # Single-page homepage
├── cv.html                    # CV page (HTML)
├── contact.html               # Contact details page
├── projects.html              # Projects overview page
├── published.html             # Publications page
├── CV_Current.pdf             # Latest CV PDF
├── js/
│   ├── jquery-3.4.1.min.js
│   └── bootstrap.bundle.min.js
└── README.md                  # This file
```

---

## ⚙️ Getting Started

1. **Clone** the repository:

   ```bash
   git clone https://github.com/paulocilasjr/personal-webpage.git
   cd personal-webpage
   ```

2. **Open** any `.html` file in your browser or serve via a local HTTP server for full navigation:

   ```bash
   # Python 3
   python -m http.server 8000
   # Then browse to http://localhost:8000
   ```

3. **Edit** content:

   - Update text directly in the HTML.
   - Replace `CV_Current.pdf` with a new version to update CV.
   - Add or remove publications in `published.html`.

4. **Deploy** to any static hosting (GitHub Pages, Netlify, Vercel).

---

## 🤝 Contributing

Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss your ideas.

---

## 📜 License

This project is released under the MIT License. See [`LICENSE`](LICENSE) for details.

---

> _Built and maintained by Paulo C. M. Lyra Jr._
```

