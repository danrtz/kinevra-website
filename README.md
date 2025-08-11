# Kinevra - SAP Integration & BTP Solutions Website

A modern, visually stunning website for Kinevra, specializing in SAP integration and Business Technology Platform (BTP) services.

## 🚀 Features

- **Modern Dark Theme**: Sleek black background with vibrant gradient accents
- **Apple System Fonts**: Clean, professional typography using SF Pro Display
- **Responsive Design**: Fully responsive across all devices
- **Glass Morphism**: Modern glass-effect cards with backdrop blur
- **Smooth Animations**: Engaging scroll animations and hover effects
- **SEO Optimized**: Built with best practices for search engine optimization
- **Fast Performance**: Static site generation for lightning-fast load times

## 📄 Pages

- **Home**: Hero section with services overview, technology stack, and call-to-action
- **About**: Company mission, values, and approach
- **Privacy Policy**: Comprehensive privacy policy
- **Terms of Service**: Detailed terms and conditions
- **Blog**: SAP/BTP focused technical articles

## 🎨 Design Elements

- **Color Palette**:
  - Primary: #007AFF (Apple Blue)
  - Secondary: #5856D6 (Purple)
  - Accent: #FF3B30 (Red)
  - Success: #34C759 (Green)
  - Background: Pure black with gradient overlays

- **Visual Effects**:
  - Floating blur backgrounds
  - Gradient text effects
  - Glass morphism cards
  - Smooth hover transitions
  - Animated elements on scroll

## 🛠️ Tech Stack

- **Framework**: Astro
- **Styling**: Custom CSS with CSS Variables
- **Deployment**: Cloudflare Pages
- **Content**: Markdown for blog posts
- **Build**: Vite

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/kinevra-website.git
cd kinevra-website

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 🚀 Deployment

### Cloudflare Pages

1. Push your code to GitHub
2. Connect your GitHub repository to Cloudflare Pages
3. Set build command: `npm run build`
4. Set build output directory: `dist`
5. Deploy!

### Manual Deployment

```bash
# Build the project
npm run build

# Deploy using Wrangler
npm run deploy
```

## 📧 Contact Configuration

All contact forms and links redirect to: `daniel@kinevra.com`

To change the contact email, update the `CONTACT_EMAIL` constant in `src/consts.ts`

## 🎯 Services Offered

- **SAP Integration**: API Management, Data Migration, Process Automation
- **BTP Solutions**: Cloud Foundry Apps, Integration Suite, Analytics Cloud
- **Consulting & Support**: Architecture Design, Best Practices, 24/7 Support

## 📝 Blog Content

The blog includes technical articles about:
- Getting Started with SAP Business Technology Platform
- SAP S/4HANA Cloud Integration Best Practices
- Building Modern Applications with SAP CAP

## 🔧 Customization

### Update Company Information
Edit `src/consts.ts` to change:
- Site title
- Site description
- Company name
- Contact email

### Modify Styles
Edit `src/styles/global.css` to customize:
- Colors (CSS variables in `:root`)
- Typography
- Animations
- Spacing

### Add New Pages
1. Create a new `.astro` file in `src/pages/`
2. Use the `Layout` component for consistent styling
3. Add navigation links in `src/components/Header.astro`

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                           | Action                                           |
| :-------------------------------- | :----------------------------------------------- |
| `npm install`                     | Installs dependencies                            |
| `npm run dev`                     | Starts local dev server at `localhost:4321`      |
| `npm run build`                   | Build your production site to `./dist/`          |
| `npm run preview`                 | Preview your build locally, before deploying     |
| `npm run astro ...`               | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help`         | Get help using the Astro CLI                     |
| `npm run deploy`                  | Deploy your production site to Cloudflare        |

## 📄 License

This project is proprietary and confidential.

## 👨‍💻 Developer

Built with ❤️ for Kinevra

---

For any questions or support, please contact daniel@kinevra.com
