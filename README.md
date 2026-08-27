<h1 align="center">Hi 👋, I'm Shubham Mishra</h1>

<p align="center">
  <strong>Computer Science Engineering Student • Python • AI/ML • Web Development • Cybersecurity</strong>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=2F81F7&center=true&vCenter=true&width=650&lines=Computer+Science+Engineering+Student;Python+%7C+AI+%7C+Machine+Learning;Building+Real+World+Projects;Exploring+Web+Development;Exploring+Cybersecurity;Always+Learning%2C+Always+Building" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://shubham-mishra-github-io.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-Visit-2F81F7?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://www.linkedin.com/in/shubham-mishra-54a1ab294/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/5hubhamMishra">
    <img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

---

## 👨‍💻 About Me

I'm a Computer Science Engineering student who enjoys building practical projects and exploring different areas of software development.

My current interests include **Python, Machine Learning, Artificial Intelligence, Web Development, and Cybersecurity**.

I enjoy learning by building projects, experimenting with new technologies, and improving my problem-solving and programming skills.

- 🎓 Computer Science Engineering Student
- 🐍 Interested in Python and Machine Learning
- 🤖 Exploring Artificial Intelligence
- 🌐 Learning and building Web Applications
- 🔐 Exploring Cybersecurity and Ethical Hacking
- 🚀 Building practical projects and experimenting with new technologies
- 📚 Continuously improving my programming and problem-solving skills

---

## 🛠️ Tech Stack

### 💻 Programming Languages

<p>
  <img src="https://skillicons.dev/icons?i=python,c,cpp,js" alt="Programming Languages"/>
</p>

### 🌐 Web Development

<p>
  <img src="https://skillicons.dev/icons?i=html,css,react,django,tailwind" alt="Web Development"/>
</p>

### 🤖 AI / Machine Learning

<p>
  <img src="https://skillicons.dev/icons?i=python" alt="Python"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn"/>
</p>

### 🗄️ Databases & Tools

<p>
  <img src="https://skillicons.dev/icons?i=mysql,sqlite,git,github,vscode,postman" alt="Tools"/>
</p>

---

# 🚀 Featured Projects

Below are some of the major projects I have developed while exploring Artificial Intelligence, Machine Learning, Web Development, Software Engineering, Computer Vision, and intelligent application development.

---

## 🛒 AI-Commerce — AI-Native E-Commerce & Marketplace Platform

<p>
  <a href="https://github.com/5hubhamMishra/-ai-commerce">
    <img src="https://img.shields.io/badge/GitHub-View_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repository"/>
  </a>
</p>

A production-oriented **AI-native e-commerce and marketplace platform** designed around a complete commerce architecture combined with intelligent shopping capabilities.

Instead of functioning only as a traditional product catalog, the platform integrates **personalized product discovery, hybrid recommendation systems, semantic search, and a conversational shopping assistant called ShopAI**.

The project uses a multi-application architecture consisting of a **Next.js web storefront and administration interface**, a **NestJS backend API**, and a **React Native / Expo mobile application**.

The web and mobile applications communicate with the same backend API contracts, helping maintain consistent commerce and AI functionality across different platforms.

The commerce foundation includes authentication, authorization, catalog management, shopping carts, wishlists, checkout, payments, orders, and other marketplace-related functionality.

The backend follows a modular architecture with REST APIs, Role-Based Access Control, commerce-domain logic, shared validation, reusable TypeScript models, and structured application services.

One of the major focuses of the project is intelligent product discovery. The architecture supports personalized recommendations, hybrid recommendation strategies, semantic product search, and the **ShopAI conversational shopping interface**.

The repository follows a monorepo structure containing reusable packages for shared TypeScript types, configuration, request/response validation, and API communication.

PostgreSQL is used for persistent commerce data while Redis supports fast-access services and supporting application functionality.

Docker-based development infrastructure is included to provide reproducible PostgreSQL and Redis environments during local development.

### ✨ Major Features

- AI-powered personalized product discovery
- Hybrid recommendation architecture
- Semantic product search
- ShopAI conversational shopping assistant
- Product catalog management
- Authentication and authorization
- Role-Based Access Control
- Shopping cart
- Wishlist management
- Checkout workflow
- Payment functionality
- Order management
- Marketplace functionality
- Web storefront
- Administrative dashboard
- Mobile shopping application
- Shared API contracts
- Shared TypeScript types
- Request/response validation
- Modular backend architecture
- PostgreSQL database
- Redis integration
- Docker-based local development

### 🏗️ Architecture

`Next.js Web Application → NestJS REST API → PostgreSQL / Redis`

`React Native Mobile Application → Shared API Contracts → NestJS Backend`

### 🛠️ Technologies

**Next.js • React • TypeScript • NestJS • React Native • Expo • PostgreSQL • Redis • Docker • REST API • RBAC • AI Recommendations • Semantic Search**

---

## 🤖 VisionAI — Safety-Focused Local Desktop Assistant

<p>
  <a href="https://github.com/5hubhamMishra/VISIONAI">
    <img src="https://img.shields.io/badge/GitHub-View_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repository"/>
  </a>
</p>

**VisionAI** is a local-first Windows desktop assistant designed around controlled capability execution, privacy, permissions, and system safety.

The system is designed to eventually support interaction through **voice commands, hand gestures, keyboard input, and pointer interactions**.

Instead of allowing the assistant to freely execute arbitrary system commands, VisionAI uses a **registered capability and policy-gated execution architecture**.

User requests are interpreted and checked against deterministic safety and permission rules before the requested capability can execute.

The current implementation contains a locally verified safety foundation and a trusted runtime.

The console interface can execute policy-controlled capabilities including system-information requests, capability discovery, help functionality, cooperative stop requests, opening allowlisted desktop applications, opening approved browser or search destinations, and controlling approved media functionality.

VisionAI also contains an early desktop graphical interface. Both the graphical interface and console use the same policy-controlled execution path, helping centralize security rules instead of implementing separate safety logic for each interface.

The project contains extensive documentation covering architecture, security, threat modeling, testing, environment setup, development workflows, migration rules, release information, and end-user operation.

A major design philosophy behind VisionAI is that **user safety, privacy, reliability, correctness, accessibility, and explicit permissions take priority over simply increasing the number of available assistant features**.

### ✨ Major Features

- Local-first desktop assistant
- Policy-gated capability execution
- Registered capabilities
- Allowlisted applications
- Deterministic safety rules
- Permission-controlled execution
- Console-based assistant runtime
- Desktop graphical interface
- System-information capabilities
- Application launching
- Browser destination launching
- Search destination support
- Media-control functionality
- Capability discovery
- Capability help system
- Cooperative stop requests
- Shared GUI and console execution architecture
- Security documentation
- Threat-model documentation
- Testing documentation
- Planned voice-command interface
- Planned hand-gesture interaction

### 💻 Platform

**Windows 10 / Windows 11**

### 🛠️ Technologies

**Python 3.12 • Desktop Applications • AI Assistant Architecture • Security Engineering • Policy Engines • Human-Computer Interaction • Voice Interfaces • Computer Vision**

---

## 💻 PaperCode — Terminal-Based Coding Agent

<p>
  <a href="https://github.com/5hubhamMishra/papercode">
    <img src="https://img.shields.io/badge/GitHub-View_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repository"/>
  </a>
</p>

**PaperCode** is a terminal-based coding agent designed to work with different **OpenAI-compatible AI providers**.

Instead of being permanently connected to a single AI provider, users can configure their own provider, API endpoint, API key, and model.

The architecture can work with OpenAI-compatible providers such as OpenAI, OpenRouter, Groq, Together, DeepSeek, and locally hosted Ollama environments.

PaperCode operates directly inside software repositories and can inspect files, search source code, modify files, and execute approved terminal commands.

A major feature of PaperCode is the separation between **BUILD mode and PLAN mode**.

BUILD mode provides development capabilities, while PLAN mode is designed as a read-only environment. Write, edit, and shell execution capabilities are unavailable to the model while PLAN mode is active.

This makes it possible to ask the coding agent questions such as how a repository could be modified without allowing the agent to actually change the source code.

Repository exploration tools such as `read`, `ls`, `glob`, and `grep` can operate without destructive modifications.

Operations including `write`, `edit`, and `bash` require approval before execution.

File operations are also restricted to the directory from which PaperCode was launched, providing additional protection against unintended filesystem access.

The application provides persistent conversation sessions, model switching, provider management, reusable skills, command palettes, themes, context compaction, custom system prompts, file autocomplete, and terminal keyboard shortcuts.

PaperCode also includes a reusable **skills system** that allows developers to define global or project-specific slash-command prompts.

For example, reusable workflows such as code reviews can be configured once and invoked later through a custom slash command.

The project also contains an extensive automated testing system covering areas such as permission enforcement, PLAN-mode restrictions, streamed tool-call reconstruction, filesystem path protection, configuration handling, sessions, UI behavior, and end-to-end provider communication.

### ✨ Major Features

- Terminal coding assistant
- OpenAI-compatible API support
- Multiple AI-provider support
- Custom API endpoints
- Custom model selection
- BUILD mode
- PLAN mode
- Read-only repository analysis
- Repository file reading
- Repository searching
- File creation
- File editing
- Shell-command execution
- Permission gates
- Filesystem path confinement
- Persistent conversations
- Session resume
- Provider management
- Model switching
- Custom reusable skills
- Global skills
- Project-specific skills
- Slash commands
- Multiple terminal themes
- Command palette
- File autocomplete
- Context compaction
- Custom system prompts
- Unit testing
- Integration testing
- End-to-end testing

### 🛠️ Technologies

**TypeScript • Node.js • React Ink • Terminal UI • OpenAI-Compatible APIs • SSE • CLI Development • Automated Testing**

---

## 🌌 The Universe of Dad — Interactive 3D Birthday Experience

<p>
  <a href="https://github.com/5hubhamMishra/something">
    <img src="https://img.shields.io/badge/GitHub-View_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repository"/>
  </a>
</p>

**The Universe of Dad** is an immersive cinematic **3D interactive birthday experience** built as a digital journey instead of a traditional static birthday webpage.

The website uses a persistent WebGL environment to create a continuous scroll-driven journey through different parts of a father's life.

The experience contains **eleven chapters** covering areas such as personal history, family, memories, achievements, lessons, personality, future dreams, and a final birthday message.

Instead of hardcoding personal information directly into the React components, the personalization system stores names, photographs, stories, quotations, dates, milestones, family information, memories, achievements, lessons, future dreams, audio paths, and the final birthday message inside a centralized JSON configuration file.

This architecture makes it possible to personalize the complete experience without modifying the underlying components.

The 3D environment uses a persistent **React Three Fiber Canvas**. Different chapters occupy different positions inside the virtual world, while the camera moves through the experience according to the user's scroll position.

HTML content and the WebGL environment remain synchronized throughout the experience.

Zustand provides shared state between the 3D world and DOM-based interface components.

The shared state manages functionality such as chapter navigation, family-star selection, audio controls, and hidden-memory interactions.

The project also considers performance and accessibility.

Particle counts, rendering resolution, post-processing effects, and visual complexity can automatically scale down for mobile devices and users who prefer reduced motion.

The site includes private authentication with password hashing, Redis-backed password management, environment-based configuration, and email-based one-time password recovery.

### ✨ Major Features

- Immersive 3D environment
- WebGL rendering
- Eleven story chapters
- Scroll-driven storytelling
- Cinematic camera movement
- Family constellation
- Interactive memory archive
- Life timeline
- Achievements section
- Lessons and quotations
- Future-dream visualization
- Hidden memories
- Discoverable interactive content
- Audio support
- Voice-recording support
- JSON-based personalization
- Persistent React Three Fiber canvas
- Synchronized HTML and 3D interface
- Zustand state management
- Responsive rendering
- Mobile optimization
- Reduced-motion accessibility
- Username/password authentication
- Password hashing
- Redis-backed password management
- Email OTP password recovery
- Vercel deployment support

### 🛠️ Technologies

**Next.js • React • TypeScript • React Three Fiber • Three.js • WebGL • GSAP • Zustand • Redis • Resend • Vercel**

---

## 🌐 Personal Portfolio Website

<p>
  <a href="https://github.com/5hubhamMishra/shubham-mishra.github.io">
    <img src="https://img.shields.io/badge/GitHub-View_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repository"/>
  </a>

  <a href="https://shubham-mishra-github-io.vercel.app/">
    <img src="https://img.shields.io/badge/Live-Visit_Portfolio-2F81F7?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Portfolio"/>
  </a>
</p>

A complete responsive **personal portfolio website** designed to showcase my technical background, projects, skills, education, activities, resume, and contact information.

The website is built using **HTML5, CSS3, and vanilla JavaScript** without requiring a frontend framework or build system.

The portfolio follows a single-page scrolling architecture where different sections are connected through the main navigation.

The Hero section introduces my profile and includes an animated rotating subtitle together with navigation calls-to-action.

The About section presents my background and technical skill categories.

The Projects section displays project cards containing project descriptions, technology information, GitHub repositories, and live demonstrations where available.

The Resume section provides access to my downloadable resume and timeline-based information about education and certifications.

Additional sections present extracurricular activities, contact details, social profiles, and a contact form.

JavaScript is used extensively throughout the website to provide interactive frontend behavior.

The website includes responsive hamburger navigation, smooth scrolling, hero typing animations, scroll-position tracking, active navigation highlighting, scroll-triggered animations, project-card interactions, form validation, notification messages, navbar effects, parallax behavior, and a back-to-top button.

The CSS architecture uses reusable custom properties for colors, spacing, typography, transitions, shadows, and other design values.

The Projects section uses responsive CSS Grid behavior to automatically reorganize project cards depending on available screen width.

The website is deployed publicly using **Vercel**.

### ✨ Major Features

- Responsive single-page interface
- Animated Hero section
- Typing animation
- About section
- Technical skills display
- Project showcase
- GitHub project links
- Live project links
- Resume download
- Education timeline
- Certification information
- Activities section
- Contact information
- Contact form
- Client-side validation
- Responsive hamburger menu
- Scroll progress indicator
- Smooth scrolling
- Active navigation highlighting
- Scroll-triggered animations
- Project-card hover effects
- Navbar scroll effects
- Desktop parallax effects
- Back-to-top button
- Reusable CSS variables
- Responsive CSS Grid
- Vercel deployment

### 🛠️ Technologies

**HTML5 • CSS3 • JavaScript • DOM APIs • Intersection Observer • Responsive Design • Git • GitHub • Vercel**

---

## 🩺 Skin Cancer Classification

<p>
  <a href="https://github.com/5hubhamMishra/Skin-Cancer-Classification">
    <img src="https://img.shields.io/badge/GitHub-View_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repository"/>
  </a>
</p>

A **Deep Learning and Computer Vision project** focused on applying neural-network techniques to skin-cancer image classification.

The repository contains Jupyter Notebook implementations dedicated to developing and experimenting with a deep-learning model for skin-cancer classification and detection.

The project explores how medical images can be processed and analyzed using machine-learning and deep-learning approaches.

The objective is to develop models capable of learning visual patterns from skin-lesion images and using those patterns for classification.

The notebook-based workflow provides an interactive environment for experimenting with data preprocessing, model development, model training, evaluation, and iterative improvements.

The project provides practical experience applying artificial intelligence techniques to healthcare-oriented computer-vision problems.

### 🔬 Major Areas

- Skin-lesion image analysis
- Medical image classification
- Deep-learning experimentation
- Neural-network development
- Computer vision
- Image preprocessing
- Model training
- Model evaluation
- Jupyter Notebook experimentation
- Healthcare-oriented AI

### 🛠️ Technologies

**Python • Deep Learning • Machine Learning • Computer Vision • Neural Networks • Jupyter Notebook**

---

## 🩸 Diabetes Prediction Web App

<p>
  <a href="https://github.com/5hubhamMishra/Diabetes-Prediction-Webapp">
    <img src="https://img.shields.io/badge/GitHub-View_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repository"/>
  </a>

  <a href="https://diabetespredicting.streamlit.app/">
    <img src="https://img.shields.io/badge/Live-Try_the_App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Live App"/>
  </a>
</p>

A machine-learning powered **Diabetes Prediction Web Application** designed to predict whether supplied health information corresponds to a diabetic or non-diabetic classification.

The application uses a trained **Support Vector Machine (SVM)** model for prediction.

Users provide health-related information through an interactive Streamlit interface.

The input includes parameters such as pregnancy count, glucose level, blood pressure, and other numerical health attributes expected by the trained model.

After the user submits the information, the application processes the values and passes them to the stored machine-learning classifier.

The resulting prediction is displayed directly through the Streamlit interface.

The trained model is stored as a serialized `.sav` file and loaded using Python's Pickle functionality when the application starts.

This separates the machine-learning training workflow from the deployed inference application, meaning the classifier does not have to be retrained every time the application runs.

The project demonstrates an end-to-end machine-learning workflow where a trained predictive model is integrated into an accessible browser-based application.

### ✨ Major Features

- Interactive health-data input
- Machine-learning classification
- Support Vector Machine model
- Streamlit web interface
- Serialized trained-model loading
- Real-time prediction
- Numerical parameter processing
- Browser-based ML inference
- Publicly accessible deployment

### ⚙️ Prediction Workflow

`Health Parameters → Streamlit Interface → Input Processing → Trained SVM Model → Diabetes Prediction`

### 🛠️ Technologies

**Python • Support Vector Machine • Machine Learning • Streamlit • NumPy • Pickle • Web Application Development**

---

## 📊 GitHub Statistics

<p align="center">
  <img
    src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=5hubhamMishra&theme=tokyonight"
    alt="Shubham's GitHub Statistics"
  />
  <img
    src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=5hubhamMishra&theme=tokyonight"
    alt="Shubham's Top Languages"
  />
</p>

<p align="center">
  <img
    src="https://github-readme-streak-stats.herokuapp.com/?user=5hubhamMishra&theme=tokyonight&hide_border=true"
    alt="Shubham's GitHub Streak"
  />
</p>

---

## 📈 Contribution Activity

<p align="center">
  <img
    src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=5hubhamMishra&theme=tokyonight"
    alt="Shubham's GitHub Contribution Activity"
  />
</p>

---

## ⚡ Activity Overview

<p align="center">
  <strong>GitHub Contribution Activity Overview</strong>
</p>

<p align="center">
  Commits • Code Reviews • Issues • Pull Requests
</p>

<p align="center">
  <a href="https://github.com/5hubhamMishra">
    View my live GitHub Activity Overview
  </a>
</p>

---

## 📋 GitHub Profile Summary

<p align="center">
  <img
    src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=5hubhamMishra&theme=tokyonight"
    alt="GitHub Profile Details"
  />
</p>

<p align="center">
  <img
    src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=5hubhamMishra&theme=tokyonight"
    alt="Repositories Per Language"
  />
  <img
    src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=5hubhamMishra&theme=tokyonight"
    alt="Most Used Languages"
  />
</p>

<p align="center">
  <img
    src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=5hubhamMishra&theme=tokyonight"
    alt="GitHub Statistics Summary"
  />
  <img
    src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=5hubhamMishra&theme=tokyonight&utcOffset=5.5"
    alt="Productive Time"
  />
</p>

---

## 🎯 Current Goals

- 📚 Strengthen Data Structures & Algorithms
- 🤖 Build more practical AI/ML projects
- 🌐 Improve Web Development skills
- 🔌 Learn and build REST APIs
- 🔐 Explore Cybersecurity and Ethical Hacking
- 🧠 Learn more about Artificial Intelligence
- 🤝 Start contributing to Open Source
- 🚀 Build projects that solve real-world problems

---

## 🐍 Contribution Snake

<p align="center">
  <img
    src="https://raw.githubusercontent.com/5hubhamMishra/5hubhamMishra/output/github-contribution-grid-snake-dark.svg"
    alt="GitHub Contribution Snake"
  />
</p>

---

## 🤝 Let's Connect

<p align="center">

  <a href="https://shubham-mishra-github-io.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-2F81F7?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/>
  </a>

  <a href="https://www.linkedin.com/in/shubham-mishra-54a1ab294/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>

  <a href="https://github.com/5hubhamMishra" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>

</p>

<p align="center">
  <i>Thanks for visiting my profile! ⭐</i>
</p>
