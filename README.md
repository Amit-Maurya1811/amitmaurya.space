# Amit Maurya Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## 🌟 Features

- **Responsive Design** - Works perfectly on all devices
- **Modern UI** - Clean and professional design
- **Interactive Elements** - Smooth animations and transitions
- **Project Showcase** - Filter and display your projects
- **Contact Form** - Let visitors get in touch
- **Fast Loading** - Optimized for performance

## 📁 Project Structure

```
portfolio/
│── index.html          # Homepage
│── about.html          # About page
│── projects.html       # Projects showcase
│── contact.html        # Contact page
│── css/
│   └── style.css      # All styling
│── images/            # Your images
│── js/
│   └── script.js      # JavaScript functionality
└── README.md
```

## 🚀 Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right and select "New repository"
3. Name it: `your-username.github.io` (or any name you prefer)
4. Make it **Public**
5. Click "Create repository"

### Step 2: Push Your Code

Open your terminal in the project folder and run:

```bash
git init
git add .
git commit -m "Initial commit: Portfolio website"
git branch -M main
git remote add origin https://github.com/your-username/your-repo-name.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section
4. Under "Source", select **main** branch
5. Click **Save**
6. Your site will be published at: `https://your-username.github.io/your-repo-name/`

## 🌐 Connecting Your Hostinger Domain

### Method 1: Using Custom Domain on GitHub Pages

1. In your repository **Settings** → **Pages**
2. Under "Custom domain", enter your domain: `amitmaurya.space`
3. Click **Save**
4. Create a file named `CNAME` in your project root with just your domain:
   ```
   amitmaurya.space
   ```

5. In Hostinger DNS settings:
   - Add an **A Record**:
     - Type: A
     - Name: @
     - Points to: `185.199.108.153`
   - Add another **A Record**:
     - Type: A
     - Name: @
     - Points to: `185.199.109.153`
   - Add another **A Record**:
     - Type: A
     - Name: @
     - Points to: `185.199.110.153`
   - Add another **A Record**:
     - Type: A
     - Name: @
     - Points to: `185.199.111.153`
   - Add a **CNAME Record**:
     - Type: CNAME
     - Name: www
     - Points to: `your-username.github.io`

6. Wait 24-48 hours for DNS propagation

### Method 2: Using Hostinger Hosting

If you prefer to use Hostinger's hosting instead:

1. Log in to Hostinger
2. Go to **File Manager** or use **FTP**
3. Upload all files to `public_html` folder
4. Your site will be live at `amitmaurya.space`

## ✏️ Customization

### Update Your Information

1. **Personal Details**: Edit the HTML files to replace "Amit Maurya" with your information
2. **Social Links**: Update social media links in all HTML files
3. **Projects**: Add your actual projects in `projects.html`
4. **Contact Info**: Update email and phone in `contact.html`
5. **Images**: Add your photos to the `images/` folder

### Change Colors

Edit the CSS variables in `css/style.css`:

```css
:root {
    --primary-color: #6366f1;    /* Main color */
    --secondary-color: #8b5cf6;  /* Secondary color */
    --dark-color: #1e293b;       /* Dark text */
    --light-color: #f8fafc;      /* Background */
}
```

### Add Email Functionality

To make the contact form actually send emails:

1. Sign up for [EmailJS](https://www.emailjs.com/) (free)
2. Get your Service ID and Template ID
3. Add EmailJS script in your HTML:
   ```html
   <script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
   ```
4. Uncomment the EmailJS code in `js/script.js` and add your credentials

## 📱 Pages Overview

- **Home** (`index.html`) - Hero section with introduction and skills
- **About** (`about.html`) - Your story, experience, and skills bars
- **Projects** (`projects.html`) - Portfolio showcase with filters
- **Contact** (`contact.html`) - Contact form and information

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS Grid & Flexbox)
- JavaScript (ES6+)
- Font Awesome Icons

## 📝 To-Do After Setup

- [ ] Add your profile photo to `images/profile.jpg`
- [ ] Add project screenshots to `images/` folder
- [ ] Update all personal information in HTML files
- [ ] Update social media links
- [ ] Customize colors and styles
- [ ] Set up email functionality (optional)
- [ ] Add Google Analytics (optional)
- [ ] Test on different devices

## 🌟 Tips

- Keep your content updated regularly
- Optimize images before uploading (use tools like TinyPNG)
- Test your site on multiple browsers
- Make sure all links work
- Update your projects as you complete new ones

## 📧 Need Help?

If you need help with deployment or customization, feel free to reach out!

## 📄 License

This template is free to use for personal and commercial projects.

---

**Good luck with your portfolio! 🚀**
