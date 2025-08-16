# Fashion Guru AI 👗🤖

Fashion Guru AI is an intelligent fashion assistant that helps users style outfits by suggesting the best combinations of clothes, shoes, and colors. Users can either **generate new fashion ideas** or **upload images of their clothes**, and the AI will guide them with styling suggestions.

## Features
- Upload clothing images and get suggestions on matching outfits.
- Generate fashion recommendations using AI.
- Supports clothing, shoes, and color palette matching.
- Built with **Groq AI** for fast and intelligent recommendations.
- Deployed on **Netlify** for easy web access.

## Tech Stack
- **Frontend:** React + Tailwind CSS
- **Backend / AI:** Python (Groq AI API)
- **Deployment:** Netlify

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/bellonbits/fashion-guru-ai.git
   cd fashion-guru-ai
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:  
   Create a `.env` file in the root directory and add your **Groq AI API key**:
   ```env
   GROQ_API_KEY=your_api_key_here
   ```

4. Run the development server:
   ```bash
   npm run dev
   ```

## Deployment

This project is deployed on **Netlify**.

To deploy manually via terminal:
```bash
netlify login
netlify init
netlify deploy --prod
```

## 📸 Usage
1. Upload your clothes or shoes image.
2. AI suggests the best outfit combination.
3. Get instant style recommendations.

## Future Improvements
- Add support for accessories (bags, watches, jewelry).
- Personalize recommendations based on body type & event.
- Save outfits to personal wardrobe.

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

## License
MIT License - free to use and modify.

---

Made with ❤️ by [Peter Gatitu Mwangi]
