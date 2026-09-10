# ARoZENIX PHARMACEUTICALS - Brand Guidelines

## 🎨 Visual Identity

### Logo
- **Symbol**: 💊 (Pill icon)
- **Style**: Modern, professional
- **Colors**: Gradient Blue to Green
- **Usage**: Website header, documentation

### Color Palette

#### Primary Colors
| Color Name | Hex Code | RGB | Usage |
|------------|----------|-----|-------|
| Medical Blue | #0066CC | 0, 102, 204 | Primary brand color, buttons, links |
| Emerald Green | #00A86B | 0, 168, 107 | Health accent, success states |
| Dark Navy | #1a2332 | 26, 35, 50 | Headlines, body text |

#### Secondary Colors
| Color Name | Hex Code | RGB | Usage |
|------------|----------|-----|-------|
| Light Background | #f8fafc | 248, 250, 252 | Backgrounds, cards |
| Border Blue | #e0e7ff | 224, 231, 255 | Borders, dividers |
| Text Gray | #556983 | 85, 105, 131 | Body text, descriptions |
| Accent Coral | #FF6B6B | 255, 107, 107 | Alerts, attention (optional) |

### Gradients

```css
/* Primary Gradient */
background: linear-gradient(135deg, #0066CC 0%, #00A86B 100%);

/* Hero Background */
background: linear-gradient(135deg, #f8fafc 0%, #e0f2ff 50%, #f0ffe0 100%);

/* Subtle Gradient */
background: linear-gradient(135deg, rgba(0, 102, 204, 0.05), rgba(0, 168, 107, 0.05));
```

---

## 🔤 Typography

### Font Family
- **Primary**: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
- **Fallback**: Arial, Helvetica, sans-serif

### Font Weights
- **Light**: 300 (descriptions)
- **Regular**: 400 (body text)
- **Medium**: 500 (secondary text)
- **Semi-Bold**: 600 (subheadings)
- **Bold**: 700 (normal text emphasis)
- **Extra Bold**: 800 (section headings)
- **Black**: 900 (main headlines)

### Font Sizes
| Use Case | Size | Weight |
|----------|------|--------|
| Main H1 | 42-72px (clamp) | 900 |
| Section H2 | 38-42px | 900 |
| Card H3 | 18-27px | 700 |
| Body Text | 14-17px | 400-600 |
| Small Text | 11-13px | 600 |

---

## 🎯 Design Principles

### 1. Healthcare First
- Trust and reliability are paramount
- Clean, professional aesthetic
- Patient-centric approach
- Accessibility always considered

### 2. Modern & Professional
- Contemporary design patterns
- Smooth animations
- Quality over quantity
- Minimalist approach

### 3. Responsive & Accessible
- Mobile-first design
- Keyboard navigation support
- Color contrast compliance (WCAG AA)
- Clear call-to-action elements

### 4. Performance
- Fast loading times
- Optimized assets
- Minimal dependencies
- Efficient code

---

## 📐 Layout Guidelines

### Grid System
- **Desktop**: 12-column grid
- **Tablet**: 6-column grid
- **Mobile**: 1-column layout
- **Gutter**: 25-30px
- **Max Width**: 1200px

### Spacing
- **Section Padding**: 85-90px vertical
- **Card Padding**: 25-45px
- **Element Gap**: 15-30px
- **Typography Margin**: 10-25px

### Border Radius
- **Small Elements**: 6-8px
- **Medium Elements**: 12-14px
- **Large Elements**: 15-16px
- **Rounded**: 50px (for pills/badges)

---

## 🔘 Button Styles

### Primary Button
```css
Background: linear-gradient(135deg, #0066CC 0%, #004fa3 100%);
Color: White;
Padding: 14px 32px;
Border-radius: 8px;
Font-weight: 700;
```

### Outline Button
```css
Background: White;
Border: 2px solid #0066CC;
Color: #0066CC;
Padding: 12px 30px;
Border-radius: 8px;
Font-weight: 700;
```

### Hover States
- Transform: translateY(-3px)
- Box-shadow: Enhanced shadow
- Transition: 0.3s ease

---

## 📱 Responsive Breakpoints

```css
/* Desktop */
@media (min-width: 1200px) { /* 4-column layouts */ }

/* Tablet */
@media (max-width: 900px) { /* 2-column layouts */ }

/* Mobile */
@media (max-width: 600px) { /* 1-column layouts */ }
```

---

## 🎨 Component Examples

### Product Card
- White background
- Subtle border (#e0e7ff)
- 12-14px border-radius
- Hover: Transform up + enhanced shadow
- Icon: Colored circle background

### Feature Card
- Light gradient background
- Left border (4px) in primary color
- Subtle shadow
- Smooth transitions
- Icon/number above text

### Call-to-Action
- Gradient background (blue to green)
- Center-aligned text
- Primary button style
- Whitespace emphasis
- Large typography

---

## 📸 Photography & Imagery

### Style
- Professional healthcare imagery
- Modern, clean aesthetic
- Diverse representation
- High quality (min. 1920px width)

### Format
- JPG: Photographs
- PNG: Icons, logos
- SVG: Illustrations (when possible)
- WebP: Modern format (fallback available)

### Optimization
- Compressed without quality loss
- Responsive srcset for different devices
- Alt text required for accessibility
- Lazy loading for performance

---

## 🎭 Voice & Tone

### Messaging
- **Professional**: Medical expertise
- **Trustworthy**: Reliable and consistent
- **Caring**: Patient-focused
- **Innovative**: Forward-thinking
- **Clear**: Jargon-free communication

### Key Messages
1. Quality is Our Priority
2. Healthcare You Can Trust
3. Affordable, Accessible Medicine
4. Long-term Health Partnerships
5. Committed to Better Health

---

## ✅ Brand Compliance Checklist

- [ ] Use approved color palette
- [ ] Maintain consistent typography
- [ ] Follow spacing guidelines
- [ ] Use proper button styles
- [ ] Ensure mobile responsiveness
- [ ] Maintain professional tone
- [ ] Include proper attribution
- [ ] Test accessibility (WCAG AA)
- [ ] Optimize performance
- [ ] Verify cross-browser compatibility

---

**Version**: 1.0  
**Last Updated**: September 2024  
**Status**: Active ✅
