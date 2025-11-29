Thrift & Thrive Foundation – Static Website
https://thriftandthrive.org/

This project contains the complete static website for the Thrift & Thrive Foundation, a nonprofit organization supporting neurodiverse families through community programs, resources, and sensory-friendly initiatives.

The website is fully responsive, lightweight, and optimized for deployment on Cloudflare Pages with GitHub integration.

FEATURES

    Fully responsive layout (desktop, tablet, mobile)
    Sticky header with active page highlighting
    Mobile-friendly hamburger navigation menu
    Clean nonprofit design and accessible structure
    Lightweight static pages for fast performance
    Centralized header and footer loaded dynamically
    Easy to expand with new pages or content


<img width="1159" height="894" alt="image" src="https://github.com/user-attachments/assets/f4e68ced-c706-4696-8ae1-11651ddce2f1" />


Project Structure

    /
    ├── index.html
    ├── support.html
    ├── partner.html
    ├── volunteer.html
    ├── volunteer-signup.html
    ├── sensory-van.html
    ├── programs.html
    ├── donate.html
    ├── header.html
    ├── footer.html
    └── assets/
        └── style.css

header.html / footer.html
Injected on every page using JavaScript for easy updates.

assets/style.css
Central stylesheet controlling layout, responsiveness, color theme, and mobile navigation.

Deployment (Cloudflare Pages)

This project is designed for seamless deployment to Cloudflare Pages.

    Build Settings
    Setting	Value
    Framework preset	None
    Build command	(leave empty)
    Build output directory	/
    Root directory	/

Once connected to GitHub, Cloudflare automatically redeploys with every commit.

DEPLOYMENT (Cloudflare Pages)

Recommended build settings:

    Framework preset: None
    Build command: (leave empty)
    Build output directory: /
    Root directory: /

Cloudflare will automatically redeploy when new commits are pushed to GitHub.

MAIL ROUTING

CONTRIBUTING

    The project is easy to extend and maintain.
    You may clone, fork, or build on top of it as needed.

LICENSE

    This project is created for the Thrift & Thrive Foundation.
    Reproduction or adaptation should be done with permission.
