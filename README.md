ResumeForge – AI-Powered Resume Builder
ResumeForge is a free, browser‑based resume builder that leverages AI to help you create professional, ATS‑optimized resumes in minutes. No account is required, all processing happens locally in your browser, and your data never leaves your device.

Live Demo
Try it now: ResumeForge Live

Features
115+ Professionally Designed Templates
Filter by style, industry, and ATS compatibility. Live preview updates as you edit.

AI Content Generator
Generate professional summaries, achievement bullet points, skills, and even full cover letters using the Google Gemini API (optional, requires your own API key).

Import Existing Resume
Upload PDF, DOCX, or TXT files. The AI extracts your information and rebuilds it into any template.

Real‑time ATS Score
See your resume’s ATS compatibility score update instantly. Receive detailed feedback and actionable tips to improve.

Cover Letter Builder
Eight beautifully designed templates with AI that generates complete letters tailored to your profile.

Profile Photo Support
Upload a photo and it appears in templates that support avatars.

Export Options
Download as PDF (print‑perfect), DOCX (editable), or TXT (plain text for ATS).

100% Private & Free
All processing occurs in your browser. No data is sent to any server except the optional AI API calls.

Tech Stack
HTML5 / CSS3 – Responsive layout with a custom design system

Vanilla JavaScript – No frameworks, all logic hand‑crafted

Google Gemini API – AI text generation (optional)

html2pdf.js – Client‑side PDF generation

PDF.js – PDF text extraction for import

JSZip – DOCX parsing for import

Getting Started
Clone the repository

bash
git clone https://github.com/yourusername/ResumeForge.git
cd ResumeForge
Open the application
Simply open index.html in a modern web browser. No build step, no server required.

(Optional) Add your Gemini API Key

Obtain a free API key from Google AI Studio (sign in with Google, create a key).

Click the “AI Key” button in the top bar and paste your key.

AI features will then be enabled.

Usage
Create a resume – Choose a template, fill in your contact details, summary, experience, education, skills, etc. The live preview updates immediately.

AI assistance – Use the “AI Writer” panel to generate content, bullet points, skill suggestions, and analyze job descriptions for keyword matching.

Import – Click “Import Resume” and upload your existing file. The AI will populate the fields for you.

Export – Select PDF, DOCX, or TXT. The PDF download creates a clean, single‑page document (automatically paginates if content overflows).

Cover letter – Switch to the Cover Letter tab, fill in recipient details, and use AI to generate entire letters or individual paragraphs.

AI Integration
All AI features are powered by the Google Gemini 2.5 Flash model (or any model you configure in the code). The API key is stored only in your browser’s localStorage and is sent directly to Google’s servers. No third‑party servers are involved.

If you do not provide an API key, the resume builder works perfectly without AI features.

Contributing
Contributions are welcome. To contribute:

Fork the repository

Create a feature branch (git checkout -b feature/amazing-feature)

Commit your changes (git commit -m 'Add some amazing feature')

Push to the branch (git push origin feature/amazing-feature)

Open a Pull Request

Please follow the existing coding style and ensure your changes do not introduce breaking issues.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Credits
Icons: Heroicons

Fonts: Google Fonts (Sora, Nunito Sans)

PDF generation: html2pdf.js

PDF parsing: Mozilla PDF.js

DOCX parsing: JSZip

Made for job seekers who value privacy and professional presentation.
