Kenja Resume DOG - AI Resume Standardization Website

📋 Overview

Kenja Resume DOG (Document Generator) is a high-fidelity Single-Page Application (SPA) designed to showcase Kenja's AI-driven resume standardization technology. This website demonstrates how the product solves the "unstructured data" problem for recruiters by transforming chaotic resume formats into standardized, structured data using RAG AI.

This repository contains the complete frontend code for the marketing landing page, featuring interactive demonstrations, pricing models, and lead capture functionality.

✨ Key Features

RAG AI Architecture 2.0 Visualization: A step-by-step visual breakdown of the Retrieval-Augmented Generation process.

Interactive "Before & After" Slider: A custom JavaScript component allowing users to drag a slider to compare a messy, unstructured resume (PDF/Image) against the clean, standardized JSON output.

Bento Grid Layout: A modern CSS Grid layout highlighting key features like Speed (30s vs 30mins), Global Language Support, and Noise Filtering.

Responsive Design: Fully optimized for Desktop, Tablet, and Mobile devices with touch-friendly interactions.

Conversion Optimization:

Sticky Navigation Bar.

Floating "Try Live Demo" button that appears on scroll.

Integrated Lead Capture Form.

🛠️ Tech Stack

This project is built with a focus on simplicity, performance, and portability. It requires no build step.

Core: Semantic HTML5 & Vanilla JavaScript (ES6+).

Styling: Tailwind CSS (loaded via CDN for instant prototyping).

Icons: Lucide Icons (lightweight, vector-based icons).

Fonts: Inter (Google Fonts).

🚀 Quick Start

Since this project uses a single-file architecture with CDN dependencies, no npm install or build process is required.

Prerequisites

A modern web browser (Chrome, Firefox, Safari, Edge).

Installation

Clone the repository:

git clone [https://github.com/your-username/kenja-resume-dog.git](https://github.com/your-username/kenja-resume-dog.git)


Open the file:

Navigate to the folder.

Double-click index.html to open it in your browser.

Optional: Use a VS Code Live Server extension for hot-reloading during edits.

📂 Project Structure

kenja-resume-dog/
├── index.html       # The complete source code (HTML, CSS, JS)
└── README.md        # Project documentation


🎨 Branding & Style Guide

The design strictly adheres to the Kenja Corporate Identity:

Primary Blue: #2062eb (Headings, Primary Actions)

Accent Green: #3ec954 (Success States, Conversion Buttons)

Backgrounds: #ffffff (White) & #f4f7fa (Subtle Gray)

Typography: Inter (Sans-serif)

📱 Mobile Optimization Details

Special attention was paid to the mobile experience:

Touch-Action Handling: The comparison slider uses touch-action: none to prevent scroll conflicts on mobile devices.

Adaptive Grid: The Bento grid reflows from a 4-column layout to a single column on mobile.

Sticky Bottom CTA: On mobile screens, the "Live Demo" button anchors to the bottom of the viewport for easy thumb access.

📄 License

© 2025 Kenja Corporation. All rights reserved.

This project is a proprietary marketing asset for Kenja Corporation. Unauthorized copying or distribution is strictly prohibited.

Developed for Kenja Corporation - Enhancing AI through content management.