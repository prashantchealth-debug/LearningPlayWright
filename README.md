# AI with Claude - Chapter 1: Playwright E2E Testing

A comprehensive Playwright E2E testing project with AI-driven automation using Claude.

## 📋 Project Overview

This project demonstrates end-to-end testing using Playwright, integrated with AI capabilities for intelligent test automation and analysis.

## 📁 Project Structure

```
AI_with_claude_chapter_1/
├── tests/
│   └── example.spec.js           # Example test cases
├── playwright.config.js           # Playwright configuration
├── package.json                   # Dependencies and scripts
├── .gitignore                     # Git configuration
└── README.md                      # This file
```

## 🚀 Getting Started

### Prerequisites

- **Node.js** (v14 or higher)
- **npm** or **yarn**

### Installation

1. Clone the repository (or navigate to the project):
   ```bash
   cd AI_with_claude_chapter_1
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Install Playwright browsers:
   ```bash
   npx playwright install
   ```

## 🧪 Running Tests

Run all tests:
```bash
npm test
```

Run tests with UI mode:
```bash
npm run test:ui
```

Run tests in debug mode:
```bash
npm run test:debug
```

Run specific test file:
```bash
npx playwright test tests/example.spec.js
```

## 📝 Test Structure

Tests are located in the `tests/` directory with `.spec.js` extension. Each test file includes:
- Browser automation examples
- Element selection and interaction
- Assertions and validation
- Multi-browser support (Chrome, Firefox, Safari)

## 🌐 Browser Support

- Chromium
- Firefox
- WebKit (Safari)
- Mobile Chrome (Pixel 5)
- Mobile Safari (iPhone 12)

## 📊 Test Reports

After running tests, view the HTML report:
```bash
npx playwright show-report
```

## 🛠️ Technologies Used

- **Playwright** - Web automation and testing framework
- **Node.js** - JavaScript runtime
- **JavaScript** - Programming language
- **Claude AI** - AI-powered analysis and automation

## 📚 Learning Resources

- [Playwright Documentation](https://playwright.dev)
- [Playwright Test Documentation](https://playwright.dev/docs/intro)
- [Playwright Best Practices](https://playwright.dev/docs/best-practices)

## 📄 Configuration

### playwright.config.js

The configuration file includes:
- Test directory settings
- Browser project configurations
- Retry and parallel execution settings
- Reporter configuration
- Trace and artifact collection

## 💡 Tips

- Use `--headed` flag to see browser during test execution
- Use `--debug` flag to step through tests
- Use `@only` to run specific tests during development
- Use `--reporter=html` for detailed HTML reports

## 🔄 Continuous Integration

Tests can be run in CI environments by setting the `CI` environment variable:
```bash
CI=true npm test
```

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

Created for learning AI-driven E2E testing with Playwright and Claude.

---

**Happy Testing!** 🚀
