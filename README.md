# 📚 Monokai Pro License Generator - Educational Project

An educational web application demonstrating cryptographic hash functions and license key generation algorithms. This project showcases modern web development techniques while exploring how software licensing systems work under the hood.

## 🚀 Quick Start - License Generation

### 🌐 Auto-Generate License Keys Online

**UPDATE!!!** - Visit [https://monokai-pro-keygen.vercel.app/](https://monokai-pro-keygen.vercel.app/) to auto-generate the keys and use them on the go! 🎉

### 📋 Manual License Generation Process

To generate a Monokai Pro license manually, you'll need any email address as a starting point. Feel free to use a placeholder like `email@example.com` for testing purposes.

#### For Sublime Text 3

1. **Create MD5 Hash**: Convert your email into an MD5 hash

    - Use any MD5 hash generator tool of your choice
    - Input: `email@example.com`
    - Output: `5658ffccee7f0ebfda2b226238b1eb6e`

2. **Create License Format**:
    - Extract the first 25 characters: `5658ffccee7f0ebfda2b22623`
    - Add dashes every 5 characters: `5658f-fccee-7f0eb-fda2b-22623`

#### For Visual Studio Code

1. **Combine UUID and Email**: Merge the extension UUID with your email address

    ```
    Extension UUID: fd330f6f-3f41-421d-9fe5-de742d0c54c0
    Your Email: pouet@pouet.com
    Combined String: fd330f6f-3f41-421d-9fe5-de742d0c54c0pouet@pouet.com
    ```

2. **Hash the Combined String**: Create MD5 hash from the merged string

    - Result example: `0f2df3b3627abf1e80de8950a3d45d9e`

3. **Build License Key**:
    - Use first 25 characters: `0f2df3b3627abf1e80de8950a`
    - Add separators every 5 characters: `0f2df-3b362-7abf1-e80de-8950a`

### 🔧 Applying the License

#### Sublime Text 3

1. Open Sublime Text 3 with Monokai Pro installed
2. Go to: `Preferences > Package Settings > Theme - Monokai Pro > Settings - User`
3. Add this configuration:
    ```json
    {
    	"email": "your-email@example.com",
    	"license_key": "your-generated-license-key"
    }
    ```
4. Save the file and restart Sublime Text 3
5. You should see a thank you pop-up message ✅

#### Visual Studio Code

1. Open VS Code with Monokai Pro installed
2. Press `Ctrl+Shift+P` to open command palette
3. Search for "Monokai Pro" and select "Monokai Pro - enter license"
4. Follow the on-screen prompts to enter your email and license key
5. You should see a thank you pop-up message ✅

## 🎓 Educational Objectives

-   **Cryptographic Learning**: Understand MD5 hashing and its applications in software licensing
-   **Algorithm Design**: Explore license key formatting and validation patterns
-   **Web Development**: Practice modern HTML5, CSS3, and vanilla JavaScript
-   **UI/UX Design**: Learn glassmorphism effects and responsive design principles
-   **Security Awareness**: Understand the importance of legitimate software licensing

## 🔬 What You'll Learn

### Cryptographic Concepts

-   MD5 hash function implementation
-   String manipulation and formatting
-   UUID-based key generation
-   Hash collision considerations

### Web Technologies

-   CSS Grid and Flexbox layouts
-   CSS custom properties (variables)
-   Backdrop-filter and glassmorphism effects
-   JavaScript DOM manipulation
-   Async/await patterns
-   Clipboard API usage

### Design Patterns

-   Responsive mobile-first design
-   Dark theme implementation
-   Interactive animations and transitions
-   Toast notification systems
-   Form validation and UX feedback

## ⚠️ Educational Disclaimer

**This project is strictly for educational purposes only.**

-   Demonstrates how license generation algorithms work
-   Shows common patterns used in software licensing
-   Teaches cryptographic hash functions and their applications
-   **NOT intended for bypassing legitimate software licenses**
-   **Please support developers by purchasing official licenses**

## 🛠️ Technologies Demonstrated

-   **HTML5**: Semantic markup and accessibility
-   **CSS3**: Modern styling with animations
-   **JavaScript ES6+**: Modern syntax and APIs
-   **CryptoJS**: Third-party cryptographic library
-   **Responsive Design**: Mobile-first approach

## 🚀 Getting Started

```bash
# Clone for educational purposes
git clone https://github.com/ahmod-abdullah-nabil/monokai-pro-keygen.git

# Open the project
cd monokai-pro-keygen

# View in browser (no build process required)
open monokai-keygen-nu.vercel.app/index.html
```

## 📖 How It Works

1. **Input Processing**: Takes an email address as input
2. **Hash Generation**: Creates MD5 hash of the input
3. **Key Formatting**: Formats the hash into a readable license key pattern
4. **Display**: Shows the generated key with copy functionality

### Algorithm Breakdown

```javascript
// Sublime Text: Direct MD5 of email
hash = MD5(email);

// VS Code: MD5 of UUID + email
hash = MD5(UUID + email);

// Format: Take first 25 characters, group by 5
license = hash.substring(0, 25).match(/.{5}/g).join("-");
```

## 🎯 Learning Outcomes

After exploring this project, you should understand:

-   How cryptographic hash functions work in practice
-   Common software licensing patterns
-   Modern web development techniques
-   The importance of supporting software developers
-   Responsive design implementation
-   JavaScript animation and interaction patterns

## 📁 Project Structure

```
monokai-pro-keygen/
├── monokai-keygen-nu.vercel.app/
│   └── index.html              # Main application file
├── cdnjs.cloudflare.com/
│   └── ajax/libs/crypto-js/    # CryptoJS library
└── README.md                   # This file
```

## ✨ Features

-   **🔥 Modern UI Design**: Clean interface with gradient animations
-   **🌙 Dark Theme**: Custom color scheme with glassmorphism effects
-   **📱 Responsive Design**: Works on all devices
-   **⚡ Real-time Generation**: Instant license key generation
-   **📋 Copy to Clipboard**: One-click copy functionality
-   **🎯 Dual Editor Support**: Sublime Text and VS Code
-   **⚠️ Educational Disclaimer**: Clear educational purpose statement

## 📚 Educational Resources

-   [MDN Web Docs - Crypto API](https://developer.mozilla.org/en-US/docs/Web/API/Crypto)
-   [Understanding MD5 Hash Function](https://en.wikipedia.org/wiki/MD5)
-   [Software Licensing Best Practices](https://choosealicense.com/)
-   [CSS Glassmorphism Effects](https://css-tricks.com/glassmorphism/)

## 👨‍🎓 For Educators

This project can be used to teach:

-   Web development fundamentals
-   Cryptographic concepts
-   UI/UX design principles
-   Software ethics and licensing
-   Modern JavaScript features

## 🤝 Contributing to Learning

Found ways to improve the educational value? Contributions welcome!

-   Add more detailed code comments
-   Improve algorithm explanations
-   Enhance educational documentation
-   Suggest additional learning resources

## 🌟 Live Demo

Visit the live application: [Monokai Pro License Generator](https://monokai-keygen-nu.vercel.app/)

## 📄 License

MIT License - Feel free to use for educational purposes, learning, and teaching.

## 👨‍💻 Created By

**Ahmod Abdullah** - [@ahmod-abdullah-nabil](https://github.com/ahmod-abdullah-nabil)

_"Learning through building - one algorithm at a time"_

---

**Remember**: This is an educational demonstration. Always respect software licensing and support developers by purchasing legitimate licenses from [monokai.pro](https://monokai.pro).

---

### 🔍 Code Highlights

The project demonstrates several key programming concepts:

#### MD5 Hash Generation

```javascript
function generateMD5(str) {
	return CryptoJS.MD5(str).toString();
}
```

#### License Key Formatting

```javascript
function formatLicense(hash) {
	const first25 = hash.substring(0, 25);
	return first25.match(/.{5}/g).join("-");
}
```

#### Modern CSS Features

```css
/* Glassmorphism effect */
backdrop-filter: blur(20px);

/* CSS Custom Properties */
:root {
	--accent-blue: #00d4ff;
	--accent-purple: #8b5cf6;
}

/* CSS Grid for responsive layout */
.button-group {
	display: grid;
	gap: 1rem;
}
```

This project serves as an excellent introduction to modern web development while maintaining ethical boundaries and educational focus.
