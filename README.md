# Windoverbody - Haunted Forest Fashion E-Commerce

A dark, mysterious e-commerce website for Windoverbody, featuring a haunted forest and windover bog aesthetic.

## 🌫️ Features

- **Dark Theme**: Haunted forest aesthetic with purple, green, and deep black color scheme
- **Product Catalog**: Browse clothing items with categories
- **Shopping Cart**: Add/remove items and manage quantities
- **Responsive Design**: Mobile-friendly layout
- **Animations**: Floating and glowing effects for atmospheric feel
- **Modern Stack**: Built with Next.js 14, React, and Tailwind CSS

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ installed
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Typariah/windoverbody-site.git
cd windoverbody-site
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## 📦 Project Structure

```
windoverbody-site/
├── app/
│   ├── layout.js          # Main layout wrapper
│   ├── page.js            # Home page
│   ├── globals.css        # Global styles and theme
│   ├── products/
│   │   └── page.js        # Products listing page
│   └── cart/
│       └── page.js        # Shopping cart page
├── components/
│   ├── Navigation.js      # Header navigation
│   ├── Hero.js            # Home hero section
│   ├── FeaturedProducts.js # Featured items showcase
│   ├── ProductCard.js     # Individual product card
│   ├── About.js           # About section
│   └── Footer.js          # Footer
├── hooks/
│   └── useCart.js         # Shopping cart state management
├── data/
│   └── products.js        # Product data
└── package.json           # Dependencies
```

## 🎨 Customization

### Adding Products

Edit `data/products.js`:

```javascript
{
  id: 10,
  name: 'Product Name',
  price: 99.99,
  category: 'category-name',
  description: 'Product description',
  emoji: '🟣'
}
```

### Changing Colors

Edit `app/globals.css` to modify:
- `.text-spooky` - Purple accent color (#9d4edd)
- `.text-bog` - Green accent color (#52b788)
- Background gradients in `body` selector

## 🚢 Deployment

### Deploy to Vercel (Recommended)

1. Push code to GitHub
2. Go to [Vercel](https://vercel.com)
3. Click "New Project"
4. Select your `windoverbody-site` repository
5. Click "Deploy"

Vercel will automatically deploy on every push to main!

### Deploy to Other Platforms

```bash
npm run build
npm run start
```

## 📝 TODO

- [ ] Payment integration (Stripe)
- [ ] User authentication
- [ ] Product detail pages
- [ ] Admin dashboard
- [ ] Email notifications
- [ ] Image uploads
- [ ] Product reviews
- [ ] Wishlist feature

## 🌫️ Theme Guide

- **Colors**:
  - Spooky Purple: `#9d4edd`
  - Bog Green: `#52b788`
  - Deep Black: `#0f0f0f`
  - Zinc: `#1a1a1a`

- **Fonts**: Georgia serif for that old, mysterious feel

- **Animations**: Flicker, float, and glow effects for atmosphere

## 📄 License

MIT License - feel free to use for personal or commercial projects

## 👻 Built for Grace's Windoverbody Brand

Embrace the darkness. Wear the mystery. 🌫️
