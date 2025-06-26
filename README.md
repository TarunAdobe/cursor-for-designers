# Cursor for Designers 🎨

A collection of specialized Cursor AI rules designed to help designers code more effectively, even with little to no programming experience.

## What is This?

This project contains custom rules for Cursor (the AI code editor) that make coding more accessible for designers. These rules teach the AI to:

- **Speak your language** - Understand design terms like "smooth animation," "rounded friendly UI," and "elegant layout"
- **Explain everything simply** - No confusing jargon, just plain English explanations
- **Make small, iterative changes** - No complete rewrites for tiny tweaks
- **Focus on visual results** - Prioritize what you see over complex code structure

## 🚀 Quick Start

1. **Install Cursor** - Download from [cursor.sh](https://cursor.sh)
2. **Copy the rules** - Add the rules from this project to your Cursor workspace
3. **Start designing with code** - Ask for what you want visually, and get working code!

## ✨ What Makes This Special

### Designer-Friendly Language
Instead of saying "implement a CSS transition with ease-in-out timing function," just say:
- "Make this **smooth animation**"
- "I want a **rounded friendly UI**" 
- "Create an **elegant layout**"

### Platform-Specific Help
Get ready-to-use code for:
- 🎨 **Figma Plugins** (UXP + manifest setup)
- 🖌️ **Illustrator Scripts** (ExtendScript/UXP)
- 🌐 **Web Projects** (HTML/CSS/JS)
- 🔧 **Chrome Extensions** (manifest + popup files)

### No External Dependencies First
The AI will try to build everything with basic HTML/CSS/JS before suggesting external libraries or APIs. When APIs are needed (like Adobe Firefly), you'll get:
- Complete working code examples
- Step-by-step setup instructions
- Clear comments showing where to add your API keys

## 🎯 Perfect For

- **UI/UX Designers** learning to code their designs
- **Graphic Designers** building web portfolios
- **Creative Professionals** prototyping interactive ideas
- **Design Students** bridging the design-code gap

## 💡 Example Interactions

**You say:** "I want a card that floats up when you hover over it"

**You get:**
```css
/* This makes the card gently lift up when you hover */
.card {
  transition: transform 0.3s ease-out, box-shadow 0.3s ease-out;
}

.card:hover {
  transform: translateY(-8px); /* Moves card up by 8 pixels */
  box-shadow: 0 12px 24px rgba(0,0,0,0.15); /* Adds floating shadow */
}
```

**You say:** "Make this animation feel more bouncy"

**You get:** Three different options with visual explanations of how each feels different.

## 🛠️ How to Use

1. **Start with what you see** - Describe the visual effect you want
2. **Ask for alternatives** - The AI will suggest 2-3 different approaches
3. **Make small tweaks** - Ask for color changes, spacing adjustments, etc.
4. **Build iteratively** - Add one feature at a time

## 📁 What's Included

- `cursor-rules.md` - The main rules file for Cursor
- `examples/` - Common design-to-code examples
- `templates/` - Starter templates for different platforms

## 🤝 Contributing

Have ideas for making coding even more designer-friendly? 
- Open an issue with your suggestion
- Share examples of design terms that should be supported
- Contribute templates for new platforms

## 📚 Learn More

- [Cursor Documentation](https://docs.cursor.sh)

---

**Remember:** You don't need to be a programmer to create beautiful, interactive experiences. These rules help you speak your design language while the AI handles the technical details! ✨ 