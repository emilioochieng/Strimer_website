# 🎬 Strimer — Entertainment & Digital Services Website

Strimer is a modern, responsive entertainment and digital-services website designed to bring **streaming, sports, betting, AI tools, gaming, and digital services** together in one platform.

The website uses a dark, modern interface with responsive layouts, interactive navigation, service cards, pricing sections, and a contact form.

---

##  Features

### 🎥 Streaming

* Access to entertainment and streaming-related services.
* Dedicated streaming service section.
* Modern service cards for presenting available packages.

### ⚽ Sports & Betting

* Sports-focused content.
* Betting-related service section.
* Designed to accommodate sports and entertainment offers.

### 🤖 AI Tools

* Dedicated AI tools section.
* Space for showcasing AI-powered digital services.
* Designed for future integration with additional AI features.

### 🎮 Gaming

* Gaming-focused section.
* Space for gaming services, products, or promotions.

### 💰 Pricing

* Multiple pricing plans.
* Clear comparison between available packages.
* Call-to-action buttons for selecting a plan.

### 📩 Contact Form

* User-friendly contact section.
* Name, email, and message fields.
* JavaScript form handling.
* Displays a success message after submission.

### 📱 Responsive Design

The website is designed to work across:

* 💻 Desktop
* 📱 Mobile
* 📲 Tablet

---

# 🛠️ Technologies Used

The project is built using standard web technologies:

* **HTML5** — Website structure
* **CSS3** — Styling and responsive design
* **JavaScript** — Interactivity and functionality

No backend or database is required to run the current version.

---

# 📂 Project Structure

```text
Strimer/
│
├── Strimer.html
└── README.md
```

The main website is contained in:

```text
Strimer.html
```

---

# 💻 Getting Started

## 1. Clone the repository

If the project is hosted on GitHub:

```bash
git clone https://git@github.com:emilioochieng/Strimer_website.git
```

Move into the project folder:

```bash
cd strimer
```

---

## 2. Open the project in VS Code

Open the folder in Visual Studio Code:

```bash
code .
```

Alternatively:

1. Open VS Code.
2. Select **File → Open Folder**.
3. Select the Strimer_website project folder.

---

# ▶️ Running the Website

There are two simple ways to run Strimer.

### Option 1 — Open directly

Double-click:

```text
Strimer.html
```

It will open in your default browser.

### Option 2 — Use Live Server

For development, the recommended approach is using the **Live Server** extension in VS Code.

1. Install the Live Server extension.
2. Open `Strimer.html`.
3. Right-click inside the file.
4. Select **Open with Live Server**.

The website will open in your browser 

---

# 📱 Mobile Navigation

Strimer includes a responsive navigation menu.

On smaller screens, the navigation can be opened using the menu button.

The JavaScript controls the menu using:

```javascript
function toggleMenu() {
    const menu = document.getElementById('nav-menu');
    menu.classList.toggle('show');
}
```

---

# 📩 Contact Form

The website includes a front-end contact form.

The current form uses JavaScript to display a success message when the form is submitted.

```javascript
function handleSubmit(event) {
    event.preventDefault();

    const form = document.getElementById('contact-form');
    const successMsg = document.getElementById('success-message');

    form.style.display = 'none';
    successMsg.style.display = 'block';
}
```

### Important

The current implementation **does not send messages to an email server or database**.

For production, the form would need to be connected to a backend service or form-processing platform.

---

# 🔮 Future Improvements

Possible improvements include:

* [ ] User registration and login
* [ ] Database integration
* [ ] Online payments
* [ ] Subscription management
* [ ] Real streaming integration
* [ ] Sports API integration
* [ ] User dashboards
* [ ] Admin dashboard
* [ ] Backend API
* [ ] Contact form email delivery
* [ ] Authentication
* [ ] Search functionality
* [ ] Dark/light theme
* [ ] Improved accessibility
* [ ] SEO optimization
* [ ] Performance optimization

---

# 🔐 Security

The current project is primarily a **front-end demonstration website**.

If deployed as a production platform, additional security measures should be implemented, including:

* Secure authentication
* Server-side validation
* HTTPS
* Secure payment processing
* Input sanitization
* API authentication
* Database security
* Rate limiting

---

# 🌐 Deployment

The static website can be deployed using platforms such as:

* GitHub Pages
* Netlify
* Vercel
* Cloudflare Pages
* Any traditional web hosting provider

Because the current website is primarily HTML, CSS, and JavaScript, no server is required for the basic version.



# 👨‍💻 Development

The project can be developed using:

* Visual Studio Code
* Google Chrome
* Microsoft Edge
* Firefox
* Live Server

Recommended workflow:

```text
Write Code
    ↓
Run with Live Server
    ↓
Test in Browser
    ↓
Inspect with Developer Tools
    ↓
Fix Issues
    ↓
Commit Changes
    ↓
Push to GitHub
```

---


# ⭐ Project Status

**Status:** 🟢 Active Development

Strimer is currently a front-end website and can be expanded into a complete digital entertainment platform by adding a backend, database, authentication, APIs, and payment infrastructure.

---

## 🤝 Contributing

Contributions and improvements are welcome.

To contribute:

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature/my-new-feature
```

3. Make your changes.
4. Commit your changes.

```bash
git add .
git commit -m "Add new feature"
```

5. Push the branch.

```bash
git push origin feature/my-new-feature
```

6. Open a Pull Request.

---

## ⭐ Support

If you find the project useful, consider giving the repository a ⭐ on GitHub.

**Built with HTML, CSS & JavaScript.**

