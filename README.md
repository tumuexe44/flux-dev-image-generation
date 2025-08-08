# flux-dev-image-generation
n8n-based automation workflow for AI-powered visual production and automatic export to Google Drive.
# Flux Dev Image Generation → Google Drive Automation

This project is a fully automated AI image generation pipeline powered by `n8n`, using the `Fal.ai API` for image generation and automatically uploading the generated images to organized folders in **Google Drive**.

---

## Features

- 🔗 Integration with Fal.ai API for AI image generation
- ☁️ Automatic upload of images to Google Drive
- 🗂️ Customizable folder structure and file naming
- 🛠️ Built with n8n – no-code/low-code workflow automation
- 📦 Modular setup for easy deployment and customization

---

## Technologies Used

- [n8n](https://n8n.io/) – Workflow automation
- [Fal.ai](https://fal.ai/) – AI image generation API
- Google Drive API – File upload & folder management
- Node.js / JSON / HTTP Request Nodes

---

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/flux-dev-image-generation.git
cd flux-dev-image-generation
2. Configure Environment
Get your Fal.ai API Key

Create a Google Cloud Project with Drive API enabled

Set up OAuth or Service Account for Google Drive

Set environment variables or add credentials in n8n for:

FAL_API_KEY

Google Drive credentials

3. Import the Workflow into n8n
Open your n8n instance

Import the .json workflow file from this repo

Adjust credentials & prompts as needed

▶Usage
Enter your desired image prompt.

The workflow sends it to Fal.ai and generates the image.

Image is saved and uploaded to the specified Google Drive folder.

(Optional) You can schedule this using Cron node or webhook triggers.

{
  "prompt": "a futuristic landscape, neon city, 4k, concept art"
}
