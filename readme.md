<h1 align="center">
Cloud-Native Streaming and Entertainment Platform
</h1>

---

## 📝 Abstract

<div align="justify">

StreamHive is a cloud-native web-based video streaming platform that replicates the core functionalities of commercial-grade OTT services. Designed with a rich frontend and integrated backend, the platform supports user registration, authentication, profile management, multimedia content browsing, and dynamic interactions. Built for scalability and smooth user experience, StreamHive mimics a modern streaming service interface — offering category-based exploration, trending content highlights, and detailed video previews.

Deployed live on AWS infrastructure, StreamHive combines PHP-based backend logic with responsive frontend components to deliver a fast and visually appealing user experience across devices. The architecture is modular, allowing future integration with cloud-based media storage, authentication systems, and video delivery networks.

</div>

---

## 🚀 Live Deployment

The application is hosted on AWS using the following services:
- 🌐 **Amazon EC2** for server hosting
- 📁 **Amazon S3** for scalable media storage
- 🔐 **Security Groups** configured for secure HTTP access
- 🔄 **Custom domain and SSL**

---

## 🎯 Key Features

- 🎬 Rich multimedia interface with show details, categories, and trending titles
- 🔐 Secure user authentication system with sign-up/login
- 🧑‍💼 Profile management including profile image update and session state handling
- 📩 Password reset interface with server-side PHP validation
- 💬 Modular HTML pages with structured navigation
- 📱 Fully responsive UI for mobile and desktop

---

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, Bootstrap, JavaScript
- **Backend**: PHP
- **Web Server**: Apache on Ubuntu (via AWS EC2)
- **Dev Tools**: VS Code, GitHub, Git Bash
- **Cloud Infrastructure**: AWS EC2 (Ubuntu Instance)

---

## 🧪 Getting Started Locally

You can test this application locally before deployment using XAMPP or WAMP:

1. Clone the repository:
   ```bash
   git clone https://github.com/Bharadwaj-1953/StreamHive.git
   ```
2. Move the project into your PHP server's root:
   - For XAMPP: `htdocs/StreamHive/`
   - For WAMP: `www/StreamHive/`

3. Open your browser at:
   ```
   http://localhost/StreamHive/index.html
   ```

---

## 📂 Project Structure

```bash
StreamHive/
├── index.html                  # Main landing page
├── login.php                   # Login form handler
├── signupvalidation.php        # Sign-up logic with form validation
├── resetvalidation.php         # Password reset handling
├── profile-image.php           # Profile image upload handler
├── profile-updation.php        # Profile update logic
├── css/                        # Stylesheets
├── js/                         # JavaScript interactions
├── fonts/                      # Custom font resources
├── images/                     # Posters, icons, and assets
├── video/                      # Local video samples or placeholders
├── manage_profile_files/       # CSS/JS resources for profile page
├── *.html                      # Rich content and user flow pages
└── readme.md                   # This documentation
```

---

## 🌍 User Flow

- **Visit Home Page**: Browse through featured and trending shows.
- **Sign Up / Login**: Create an account or access your profile.
- **Explore Shows**: View categorized content, descriptions, and mock thumbnails.
- **Manage Profile**: Update your name, image, or credentials.
- **Reset Password**: Use email input and reset form securely.

---

## 💡 Future Enhancements

- Integrate MySQL or cloud-hosted RDS for persistent user and video metadata
- Enable real-time video streaming from AWS S3 or a CDN
- Add authentication via AWS Cognito or OAuth providers
- Add rating, comment, and review sections for shows
- Develop admin dashboard to manage users and upload new media
- Integrate AI-based content recommendation engine

---

## 🔐 Security and Hosting Considerations

- PHP scripts validated with server-side checks
- Form inputs sanitized to prevent injection attacks
- Hosted securely behind AWS firewall rules with restricted port access
- AWS EC2 instance hardened with minimal package footprint

---

## 📬 Contact Information

For any detailed information, clarification, or collaboration inquiries regarding this project, feel free to reach out:

- **Email**: [manne.bharadwaj.1953@gmail.com](mailto:manne.bharadwaj.1953@gmail.com)
- **LinkedIn**: [Bharadwaj Manne](https://www.linkedin.com/in/bharadwaj-manne-711476249/)

---
