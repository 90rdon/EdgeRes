# Edge-Based Resume Scorer

## Overview

This project aims to develop a resume scoring application that leverages a lightweight edge LLM (using [mlc-ai/web-llm](https://github.com/mlc-ai/web-llm)) to analyze and score resumes uploaded by users. The application will provide users with a dashboard to manage their resumes, view scores, and receive suggestions for improvement. **User privacy is of utmost importance throughout this project.**

## Features (MVP)

*   **User Authentication:** Secure user registration, login, and "Forgot Password" functionality.
*   **Profile Management:** Edit personal details (name, email).
*   **Resume Upload & Management:** Upload multiple resume versions (PDF, DOC, DOCX) with associated names, tag resumes, store resumes locally in the browser (prioritizing user privacy), delete resumes, and re-upload/overwrite existing versions.
*   **Dashboard:** View all uploaded resumes with filename, upload date, score, and tags.
*   **Resume Scoring and Analysis:** Utilize MLC Web LLM to score resumes (0-100 or qualitative scale), provide summaries of strengths and weaknesses, and generate categorized suggestions.
*   **Resume Detail View:** Show detailed score breakdown (formatting, keywords, clarity), AI-generated improvement recommendations, and highlight problematic/improvable sections.

## Technologies Used

*   Frontend: [React, Vue.js, or Angular] (Choose one)
*   LLM: [mlc-ai/web-llm](https://github.com/mlc-ai/web-llm)
*   Local Storage: IndexedDB or Web SQL (with a focus on secure and private data handling)

## Potential Future Features

*   Target Job Matching
*   Version Comparison (consider privacy implications)
*   Download Resume Report (ensure secure and private handling)
*   In-Browser Resume Editor
*   Analytics & Feedback Loop (implement strong anonymization)
*   Data Privacy Controls (opt-out, explicit consent)
*   Secure Resume Storage (Firebase, S3)
*   User Roles/Permissions
*   Advanced Analytics
*   Integration with Job Boards (ensure secure data sharing with consent)
*   Feedback Mechanism
*   Automated Resume Formatting
*   A/B Testing
*   Progress Tracking
*   Quick filters and sorting

## Getting Started

1.  **Installation:** Provide instructions on how to install dependencies (e.g., `npm install`).
2.  **Configuration:** Explain any necessary configuration steps.
3.  **Running the Application:** Describe how to run the application (e.g., `npm start`).

## Contributing

Created and maintained by [90rdon](https://github.com/90rdon).  Contributions are welcome!

## License

MIT License

Copyright (c) 2025 [90rdon](https://github.com/90rdon)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.