# PortfolioSDK - TODO List

Use this template to create GitHub issues for planned features and improvements.

## 🐛 Current Issues

### OpenRouter Conversation Memory
**Priority:** Medium  
**Status:** Partially Working

OpenRouter doesn't support conversation history due to strict message format validation. Currently using stateless mode (each message is independent).

**Potential Solutions:**
- Investigate OpenRouter's exact message format requirements
- Try different message serialization approaches
- Consider using OpenRouter's native SDK instead of Vercel AI SDK wrapper

---

## 🎨 UI Improvements

### More Chat UI Templates
**Priority:** High

Add pre-built theme options:
- Minimal Theme
- Dark Mode Theme
- Professional Theme
- Colorful Theme
- Glassmorphism Theme
- Neumorphism Theme

### Button Placement Options
**Priority:** Medium

Add props for button positioning:
- `submitButtonPosition`: 'inside' | 'outside' | 'floating'
- `submitButtonAlignment`: 'left' | 'right' | 'center'

---

## 🌐 Platform Support

### Vanilla JavaScript Implementation
**Priority:** High

Create standalone JavaScript widget for non-React portfolios:
- Standalone `portfolio-chat-widget.js` (no dependencies)
- Web Component version (`<portfolio-chat>`)
- CDN-ready bundle
- Integration guides for Vue, Angular, Svelte

---

## 🔧 Feature Enhancements

### Better Error Handling
**Priority:** Medium
- User-friendly error messages
- Retry mechanism
- Offline mode detection
- Rate limit handling

### Advanced Customization
**Priority:** Low
- Custom message components
- Custom thinking indicator
- Animation speed controls

---

## 📚 Documentation

### Documentation Improvements
**Priority:** Medium
- Video tutorials
- Code examples for each provider
- Migration guide
- FAQ section
- Troubleshooting guide

---

## 🧪 Testing & Quality

### Testing Suite
**Priority:** Medium
- Unit tests
- Integration tests
- E2E tests
- Cross-browser testing
- Accessibility testing

---

## 🚀 Performance

### Performance Optimizations
**Priority:** Low
- Code splitting
- Lazy loading
- Bundle size optimization

---

## 🔐 Security

### Security Enhancements
**Priority:** Medium
- Input sanitization
- XSS protection
- Rate limiting
- Security best practices guide

---

## 📦 Distribution

### NPM Package
**Priority:** High
- Publish to npm as `portfoliosdk`
- CI/CD setup
- Version management
- Changelog automation

