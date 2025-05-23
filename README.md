# 🕉️ Spiritual-ai - Hindu Scripture Guidance

A comprehensive spiritual AI advisory web application that provides personalized guidance by matching user queries with authentic Hindu scriptures using advanced AI technologies.

## ✨ Features

- **🤖 AI-Powered Scripture Matching** - Intelligent matching of life questions with relevant Hindu verses
- **📚 Authentic Sacred Texts** - 59 genuine verses from Bhagavad Gita and Upanishads
- **🎯 Personalized Guidance** - Practical wisdom applications for modern life challenges
- **🕉️ Beautiful Spiritual Interface** - Sacred Om symbol branding with saffron gradients
- **📖 Sanskrit Originals** - Authentic Sanskrit verses with English translations
- **👥 Community Questions** - See what spiritual guidance others have sought

## 🛠️ Tech Stack

- **Frontend:** React, TypeScript, Tailwind CSS, shadcn/ui
- **Backend:** Node.js, Express, PostgreSQL
- **AI:** OpenAI GPT-4 for intelligent scripture matching
- **Database:** Drizzle ORM with PostgreSQL
- **Deployment:** Replit-ready

## 📖 Scripture Database

Contains 59 authentic verses from:
- **Bhagavad Gita** - Krishna's teachings to Arjuna (21 verses)
- **Upanishads** - Ancient wisdom texts (38 verses)
  - Isha Upanishad - Divine presence and renunciation
  - Katha Upanishad - Overcoming fear and choosing wisdom
  - Chandogya Upanishad - "Tat Tvam Asi" (You Are That)
  - Mundaka Upanishad - Types of knowledge for students
  - Brihadaranyaka Upanishad - "You are what your desire is"
  - And more sacred texts...

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- PostgreSQL database
- OpenAI API key

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/spiritual-ai
cd spiritual-ai
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
```bash
# Copy and configure your environment
DATABASE_URL=your_postgresql_connection_string
OPENAI_API_KEY=your_openai_api_key
```

4. Set up the database:
```bash
npm run db:push
```

5. Seed authentic scriptures:
```bash
npx tsx server/upanishads-data.ts
npx tsx server/bhagavad-gita-data.ts
```

6. Start the development server:
```bash
npm run dev
```

Visit `http://localhost:5000` to experience spiritual guidance!

## 💡 How It Works

1. **Ask Your Question** - Share life situations, academic struggles, or spiritual questions
2. **AI Scripture Matching** - Advanced AI finds relevant verses from Hindu sacred texts
3. **Receive Guidance** - Get personalized wisdom with exact scripture references
4. **Practical Steps** - Actionable advice based on ancient teachings

## 🎯 Use Cases

Perfect for guidance on:
- 📚 Academic stress and study challenges
- 😰 Anxiety and fear management
- 🎯 Life decisions and career choices
- 🧘 Spiritual growth and meditation
- 💪 Personal development and motivation
- ❤️ Relationships and family matters

## 🕉️ Sacred Wisdom Examples

> **"You have a right to perform your prescribed duty, but not to the fruits of action."**  
> *- Bhagavad Gita 2.47*

> **"You are what your deep, driving desire is. As your desire is, so is your will."**  
> *- Brihadaranyaka Upanishad 4.4.5*

> **"Lead me from the unreal to the real. Lead me from darkness to light."**  
> *- Brihadaranyaka Upanishad 1.3.28*

## 🤝 Contributing

We welcome contributions to expand our sacred text database or improve the AI guidance system! Please:

1. Fork the repository
2. Create your feature branch
3. Ensure all scripture additions are authentic and properly sourced
4. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Ancient Hindu sages and scriptural traditions
- Swami Nirmalananda Giri for Upanishad commentaries
- A.C. Bhaktivedanta Swami Prabhupada for Bhagavad Gita translations
- The timeless wisdom of Vedic literature

## 🌟 Support

If this spiritual AI helps you find guidance, please ⭐ star the repository and share it with others seeking authentic Hindu wisdom!

---

*"There is no joy in the finite; there is joy only in the Infinite."* - Chandogya Upanishad
