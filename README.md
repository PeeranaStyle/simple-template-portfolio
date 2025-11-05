# PeeranaStyle's Personal Portfolio 🖥️✨

A modern, interactive personal portfolio website built with React, TypeScript, and Tailwind CSS. Showcasing my journey as a developer passionate about clean design and efficient code.

## 🚀 Features

- **Responsive Design**: Optimized for desktop and mobile devices
- **Dark Theme**: Elegant dark mode with customizable themes
- **Smooth Animations**: Powered by Framer Motion
- **Interactive Elements**: Custom cursor, floating menu, and background effects
- **Multi-Section Layout**: Home, About, Portfolio, Skills, and Contact sections
- **TypeScript Support**: Fully typed for better development experience
- **SEO Optimized**: Meta tags and structured data

## 🛠️ Tech Stack

- **Frontend Framework**: React 19
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Icons**: FontAwesome
- **Routing**: React Router DOM
- **Build Tool**: Create React App

## 📦 Installation

1. Navigate to the project directory:
   ```bash
   cd /path-to-project
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

   The app will open at [http://localhost:3000](http://localhost:3000).

## 📜 Available Scripts

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production
- `npm run eject` - Ejects from Create React App (irreversible)

## 🎨 Customization

1. **Personal Information**: Update data in `/src/data/` JSON files:
   - `home.json` - Replace name, nickname, tagline, and profile image URL with your information
   - `about.json` - Update bio, story, interests, and profile details with your content. Replace placeholder image URLs
   - `portfolio.json` - Replace example projects with your actual projects, including real image URLs and links
   - `skills.json` - Update skills and descriptions to match your expertise. Replace placeholder image URLs
   - `contact.json` - Update email and social media links with your real contact information

2. **Styling**: Modify Tailwind classes in component files or update `tailwind.config.js`

3. **Assets**: 
   - Replace placeholder images (currently using placehold.co URLs) with your own images hosted online, or upload images to `/public/` and update the URLs in JSON files accordingly
   - Update favicon.ico, logo192.png, logo512.png in `/public/` with your branding

4. **HTML Meta Tags**: Update the title and description in `/public/index.html` to reflect your portfolio

5. **Deployment**: See deployment section below for hosting options

## 🚀 Deployment

### Netlify

1. Build the project:
   ```bash
   npm run build
   ```

2. Deploy the `build` folder to Netlify

### Vercel

1. Connect your GitHub repository to Vercel
2. Deploy automatically on push

## 📁 Project Structure

```
personal-website/
├── public/                 # Static assets
├── src/
│   ├── components/        # React components
│   ├── contexts/          # React contexts (Theme)
│   ├── data/              # JSON data files
│   ├── types/             # TypeScript types
│   └── index.tsx          # App entry point
├── package.json
├── tailwind.config.js
└── tsconfig.json
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**PeeranaStyle** - *Developer*

Hi! I'm PeeranaStyle

- Portfolio: [[your-portfolio-url](https://your-portfolio-url.com)](https://portfolio-peeranathakron.web.app/)
- GitHub: [[@your-github](https://github.com/your-github)](https://github.com/PeeranaStyle)

**Skills & Technologies:**
- Add your skills here

## 🔧 Troubleshooting

- **Build fails**: Ensure Node.js (version 14+) and npm are installed
- **Port 3000 in use**: The development server will automatically use another available port
- **Dependencies issues**: Delete `node_modules` and `package-lock.json`, then run `npm install`
- **Images not loading**: Check that image URLs in JSON files are accessible and valid

## 📝 Notes

- Placeholder images (placehold.co URLs) should be replaced with your own hosted images for production use
- Update social media links in `contact.json` with your actual profiles
- The project uses Create React App - the `npm run eject` command is irreversible
- For deployment, the `build` folder contains the production-ready files

---

*Built with ❤️ using React and TypeScript*
