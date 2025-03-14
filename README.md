# Deep Research

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Next.js 15](https://img.shields.io/badge/Next.js-15-blueviolet)](https://nextjs.org/)

**Lightning-Fast Deep Research Reports Powered by Google Gemini**

Deep Research is a cutting-edge project built with Next.js 15, leveraging the power of Google Gemini models to generate in-depth research reports in approximately 2 minutes. Utilizing advanced "Thinking" and "Flash" models with internet access, Deep Research provides rapid and insightful analysis on a wide range of topics. Your privacy is paramount – all data is processed and stored locally.

## ✨ Features

- **Rapid Deep Research:** Generates comprehensive research reports in about 2 minutes, significantly accelerating your research process.
- **Multi-platform Support**: Supports rapid deployment to Vercel, Cloudflare and other platforms.
- **Powered by Google Gemini:** Utilizes the advanced Google Gemini models for accurate and insightful analysis.
- **Thinking & Flash Models:** Employs sophisticated "Thinking" and "Flash" models to balance depth and speed, ensuring high-quality results quickly.
- **Local & Server API Support:** Offers flexibility with both local and server-side API calling options to suit your needs.
- **Privacy-Focused:** Your data remains private and secure, as all data is stored locally on your browser.
- **Multi-language Support**: English、简体中文.
- **Built with Modern Technologies:** Developed using Next.js 15 and Shadcn UI, ensuring a modern, performant, and visually appealing user experience.
- **MIT Licensed:** Open-source and freely available for personal and commercial use under the MIT License.

## 🚀 Getting Started

Follow these steps to get Deep Research up and running on your local browser.

### Prerequisites

- [Node.js](https://nodejs.org/) (version 18.18.0 or later recommended)
- [pnpm](https://pnpm.io/) or [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/u14app/deep-research.git
   cd deep-research
   ```

2. **Install dependencies:**

   ```bash
   pnpm install  # or npm install or yarn install
   ```

3. **Set up Environment Variables:**

   Create a `.env` or `.env.local` file in the root directory of your project and configure the following environment variables:

   ```env
   # Server-side Gemini API Key (Required for server API calls)
   GOOGLE_GENERATIVE_AI_API_KEY=YOUR_GOOGLE_GENERATIVE_AI_API_KEY

   # (Optional) Server API Proxy URL
   API_PROXY_BASE_URL=YOUR_API_PROXY_URL

   # (Optional) Server API Access Password for enhanced security
   ACCESS_PASSWORD=YOUR_ACCESS_PASSWORD
   ```

   **Important Notes on Environment Variables:**

   - `GOOGLE_GENERATIVE_AI_API_KEY`: **Required for using the server-side API.** You need to obtain a Google Generative AI API key from [Google AI Studio](https://aistudio.google.com/). This key should be kept secret and **never committed to your public repository.**
   - `API_PROXY_BASE_URL`: **Optional.** If you need to use a proxy server for API requests, configure this variable with your proxy server's base URL. This is relevant for server-side API calls.
   - `ACCESS_PASSWORD`: **Optional but highly recommended for server-side deployments.** Set a strong password to protect your server-side API endpoints. This password will be required to access server-side API functionalities.

   **Privacy Reminder:** These environment variables are primarily used for **server-side API calls**. When using the **local API mode**, no API keys or server-side configurations are needed, further enhancing your privacy.

4. **Run the development server:**

   ```bash
   pnpm dev  # or npm run dev or yarn dev
   ```

   Open your browser and visit [http://localhost:3000](http://localhost:3000) to access Deep Research.

## ⚙️ Configuration

As mentioned in the "Getting Started" section, Deep Research utilizes the following environment variables for server-side API configurations:

- `GOOGLE_GENERATIVE_AI_API_KEY`
- `API_PROXY_BASE_URL`
- `ACCESS_PASSWORD`

These variables are **only required if you intend to use the server-side API calling functionality.** For local API calls, no configuration is necessary beyond setting up the project.

## 🛡️ Privacy

Deep Research is designed with your privacy in mind. **All research data and generated reports are stored locally on your machine.** We do not collect or transmit any of your research data to external servers (unless you are explicitly using server-side API calls, in which case data is sent to Google's Gemini API through your configured proxy if any). Your privacy is our priority.

## 📝 License

Deep Research is released under the [MIT License](LICENSE). This license allows for free use, modification, and distribution for both commercial and non-commercial purposes.

## 🙏 Acknowledgements

- [Next.js](https://nextjs.org/) - The React framework for building performant web applications.
- [Shadcn UI](https://ui.shadcn.com/) - Beautifully designed components that helped streamline the UI development.
- [Google Gemini](https://ai.google.dev/gemini-api) - Powering the intelligent research capabilities of Deep Research.

## 🤝 Contributing

We welcome contributions to Deep Research! If you have ideas for improvements, bug fixes, or new features, please feel free to:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Submit a pull request.

For major changes, please open an issue first to discuss your proposed changes.

## ✉️ Contact

If you have any questions, suggestions, or feedback, please create a new [issue](https://github.com/u14app/deep-research/issues).
