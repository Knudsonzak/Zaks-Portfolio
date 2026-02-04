# Zak Knudson - Portfolio Website

A modern, responsive portfolio website showcasing my projects, skills, and contact information. Built with HTML5, CSS3, JavaScript, and Node.js with Express.

## 🌐 About

This is my personal portfolio website where I showcase my work as a first-year student at Thaddeus Stevens College of Technology. The site features a clean, modern design with smooth animations, an intuitive user interface, and a fully functional email contact form.

## ✨ Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Interactive Project Cards**: Flip cards displaying project details with hover effects
- **Functional Contact Form**: Working email form using Resend API to send messages directly to my inbox
- **Smooth Navigation**: Clean navigation bar with scroll-to-section functionality
- **Social Media Integration**: Links to Instagram, GitHub, and LinkedIn profiles
- **Modern UI/UX**: Contemporary design with floating shapes and gradient animations
- **Server-Side Application**: Node.js/Express backend for email functionality

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling with modern features (Grid, Flexbox, animations, gradients)
- **JavaScript**: Interactive elements, form handling, and AJAX requests
- **Ionicons**: Modern icon library
- **Font Awesome**: Additional icon support
- **Devicon**: Developer technology icons
- **Google Fonts (Inter)**: Clean, professional typography

### Backend
- **Node.js**: Server runtime environment
- **Express.js**: Web application framework
- **Resend API**: Email service for contact form
- **dotenv**: Environment variable management

## 📂 Project Structure

```
Zaks-Portfolio/
├── index.html          # Main HTML file
├── styles.css          # Desktop styles
├── mobile.css          # Mobile responsive styles
├── server.js           # Node.js/Express server
├── package.json        # Node dependencies
├── .env               # Environment variables (not committed)
├── .gitignore         # Git ignore file
├── README.md          # Project documentation
└── assets/            # Images and icons
    └── assets/
        ├── png/       # PNG images (icons, profile photo)
        └── svg/       # SVG graphics
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (comes with Node.js)
- A Resend API key (free tier available at [resend.com](https://resend.com))

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Knudsonzak/Zaks-Portfolio.git
```

2. Navigate to the project directory:
```bash
cd Zaks-Portfolio
```

3. Install dependencies:
```bash
npm install
```

4. Create a `.env` file in the root directory:
```env
EMAIL_USER=your-email@gmail.com
RESEND_API_KEY=your-resend-api-key
```

5. Start the server:
```bash
npm start
```

6. Open your browser and navigate to:
```
http://localhost:3000
```

## 🌐 Deployment

This portfolio is deployed on [Render](https://render.com). To deploy your own:

1. Push your code to GitHub
2. Create a new Web Service on Render
3. Connect your GitHub repository
4. Add environment variables in Render:
   - `EMAIL_USER`: Your email address
   - `RESEND_API_KEY`: Your Resend API key
5. Deploy!

## 📱 Sections

### Home
- Introduction and hero section
- Social media links
- Professional photo
- Gradient background design

### About Me
- Personal introduction
- Background information
- Education details

### Skills
- HTML5, CSS3, JavaScript
- Python, Java
- Bootstrap, jQuery
- MySQL

### Portfolio
- **Personal Website**: Responsive portfolio (HTML/CSS)
- **Matrix Calculator**: Functional calculator in JavaScript ([View on GitHub](https://github.com/Knudsonzak/Matrix_calculator))
- **Flappy Bird Game**: Interactive Java game ([View on GitHub](https://github.com/Knudsonzak/Flappy-Bird))
- **Ambrosia**: Restaurant website with modern design ([View Live](https://ambrosia-zxd3.onrender.com/index.html) | [View on GitHub](https://github.com/Knudsonzak/120-Final-Project))

### Contact
- Email: zakknudson6@gmail.com
- Phone: +1 (717) 615-1583
- Location: Lancaster, PA
- Working contact form with email notifications

## 🔒 Environment Variables

Required environment variables:

- `EMAIL_USER`: Email address where contact form submissions are sent
- `RESEND_API_KEY`: API key from Resend for email functionality
- `PORT`: Server port (default: 3000)

## 📧 Contact

Feel free to reach out if you have any questions or suggestions!

- **Email**: zakknudson6@gmail.com
- **GitHub**: [@Knudsonzak](https://github.com/Knudsonzak)
- **Location**: Lancaster, PA

## 🙏 Acknowledgments

- Icons from [Ionicons](https://ionic.io/ionicons) and [Font Awesome](https://fontawesome.com/)
- Fonts from [Google Fonts](https://fonts.google.com/)

**Note**: This portfolio is continuously being updated as I learn new technologies and complete new projects.

© 2026 Zak Knudson. All rights reserved.
