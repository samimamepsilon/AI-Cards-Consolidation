# Card Design System

A comprehensive collection of card components for building consistent, scalable interfaces. This system includes 19 cards categorized into **Standard Cards** (predefined structure) and **Wrapper Cards** (flexible content containers).

## 🎯 Overview

This project demonstrates a unified card design system with:
- **14 Standard Cards** - Fixed, predictable patterns perfect for componentization
- **5 Wrapper Cards** - Flexible content containers with customizable body sections

## 📁 Project Structure

```
Cards - AI Consolidation/
├── index.html          # Original card showcase
├── demo.html           # Interactive demo with filtering
├── style.css           # All card styles
├── README.md           # This file
└── CARD_CATEGORIZATION.md  # Detailed categorization analysis
```

## 🚀 Getting Started

### View the Demo

1. **Interactive Demo** - Open `demo.html` in your browser
   - Filter cards by type (Standard vs Wrapper)
   - Filter by pattern (Icon-driven, Metrics, Profile, etc.)
   - View all cards in an organized gallery

2. **Original Showcase** - Open `index.html` to see all cards in a grid layout

### Run with Live Server

```bash
# Using npx (recommended)
npx live-server --port=8080 --open=/demo.html

# Or using Python
python -m http.server 8080
```

Then navigate to `http://localhost:8080/demo.html`

## 📊 Card Categories

### Standard Cards (14)

**Icon-Driven Cards**
- Card 1: Simple Icon Card
- Card 8: Selection/Action Card
- Card 13: Source Card
- Card 17: Standard Template Card

**Metrics Cards**
- Card 2: Metrics Dashboard Card
- Card 4: Stats Grid Card
- Card 11: Count Card with Action
- Card 14: Chart Metrics Card
- Card 18: Mini Metric Cards (3 instances)

**Profile Cards**
- Card 3: Profile Summary Card

**Action/Management Cards**
- Card 9: Management Card

**Content Cards**
- Card 5: Campaign Performance Card
- Card 12: Criteria/Badge Card
- Card 15: Simple Title/Body/Footer Card

### Wrapper Cards (5)

**Profile Wrappers**
- Card 6: Detailed Profile Card (flexible body sections)
- Card 7: Extended Profile Card (flexible rows)

**Content Wrappers**
- Card 10: Content/List Card (flexible content area)

**Form Wrappers**
- Card 16: Form/Settings Card (flexible form groups)
- Card 19: Form Card (flexible form groups)

## 🎨 Design Tokens

### Colors
- **Primary**: `#0063e6`
- **Primary Light**: `#E6F1FF`, `#f0f6ff`
- **Neutrals**: `#1a1a1a`, `#737373`, `#999999`
- **Borders**: `#e6e6e6`, `#ccc`
- **Backgrounds**: `#fff`, `#F8FAFB`, `#f7f7f7`, `#F4F6F9`
- **Success**: `#22A20E`
- **Error**: `#e63946`

### Typography
- **Font**: 'Source Sans 3', sans-serif
- **Weights**: 400, 600, 700
- **Sizes**: 12px, 13px, 14px, 38px (big numbers)

### Spacing
- Base: `4px`, `8px`, `12px`, `16px`, `24px`, `36px`

### Border Radius
- Cards: `4px`
- Headers: `3px`
- Badges: `6px`
- Tags: `12px`
- Circles: `50%`

## 🔧 Usage

### Standard Cards
Standard cards have fixed structures and can be easily componentized:

```html
<!-- Example: Icon Card Pattern -->
<div class="card1">
  <div class="icon-circle"></div>
  <p class="card-header">Card Header</p>
  <p class="card-body">Body Text</p>
</div>
```

### Wrapper Cards
Wrapper cards provide structure with flexible content areas:

```html
<!-- Example: Content Wrapper Pattern -->
<div class="card10">
  <p class="c10-title">Title</p>
  <!-- Flexible content area -->
  <div class="custom-content">
    <!-- Any content structure -->
  </div>
</div>
```

## 📚 Documentation

For detailed categorization, patterns, and architecture analysis, see:
- **[CARD_CATEGORIZATION.md](./CARD_CATEGORIZATION.md)** - Complete analysis of all cards

## 🎯 Key Features

- ✅ **19 Unique Card Designs**
- ✅ **Consistent Design System**
- ✅ **Reusable Components** (badges, buttons, icons)
- ✅ **Interactive Demo** with filtering
- ✅ **Comprehensive Documentation**

## 🚧 Future Enhancements

- [ ] Component library implementation (React/Vue)
- [ ] Design system documentation site
- [ ] Interactive style guide
- [ ] Animation and interaction patterns
- [ ] Responsive variants
- [ ] Dark mode support

## 📝 Notes

- All cards follow consistent spacing and typography rules
- Standard cards are ideal for component libraries
- Wrapper cards provide flexibility for complex content needs
- Design tokens ensure visual consistency across all cards

## 🤝 Contributing

When adding new cards:
1. Identify if it's a Standard or Wrapper card
2. Follow established design tokens
3. Use consistent spacing and typography
4. Document in CARD_CATEGORIZATION.md
5. Add to demo.html with appropriate filters

---

**Created for**: AI Consolidation Project  
**Purpose**: Design system foundation and component categorization

