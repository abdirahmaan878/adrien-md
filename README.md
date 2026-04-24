# adrien-md
Adrien-MD is a powerful and intelligent multi-device WhatsApp bot designed to enhance group management and automate everyday tasks. Built for speed, reliability, and advanced control, Adrien-MD helps admins maintain order and improve group interaction effortlessly.


🤖 ADRIEN-MD
A Powerful, Modular & Lightning-Fast Multi-Device WhatsApp Bot

Unsupported image
Unsupported image
Unsupported image
Unsupported image

Unsupported image
Unsupported image
[
Unsupported image
]
🌐 Quick Links

Unsupported image
Unsupported image
Unsupported image
Unsupported image
📖 About Adrien-MD

Adrien-MD is a next-generation, open-source WhatsApp Multi-Device bot crafted for performance, reliability, and effortless customization. Built on top of the Baileys library, it offers a clean plugin architecture, a rich command suite, and seamless deployment across the most popular hosting platforms.

Whether you're automating personal chats, moderating groups, or building advanced workflows — Adrien-MD is the toolkit you need.
✨ Key Features
Category	Highlights
🔐 Authentication	Pairing code & QR code login support
🧩 Plugin System	Hot-pluggable command modules — add features without restarting
👥 Group Tools	Welcome/goodbye, antilink, antispam, kick, promote, demote
🎨 Media Magic	Sticker maker, image/video downloader, AI image generation
🌍 Downloaders	YouTube, TikTok, Instagram, Facebook, Twitter/X, SoundCloud
🤖 AI Integration	ChatGPT, Gemini & image-to-text vision capabilities
🛡️ Security	Anti-delete, anti-call, anti-bot, view-once revealer
⚡ Performance	Optimized memory usage, fast response times, low CPU footprint
🌐 Multi-Language	English, French, Spanish, Portuguese, Swahili & more
📊 Analytics	Built-in usage stats and performance monitoring
🔑 Pairing Code Setup

    Pairing Code lets you connect Adrien-MD to your WhatsApp account without scanning a QR code — perfect for hosting on remote servers, mobile devices, or environments where you can't display a QR.

📱 Step-by-Step Instructions
1️⃣ Generate Your Pairing Code

Run the bot with the pairing flag:

npm start -- --pair

Or, if you prefer environment variables:

PAIRING_NUMBER=2348012345678 npm start

    Replace 2348012345678 with your full international WhatsApp number — no +, no spaces, no dashes.

2️⃣ Get the Code

Once the bot starts, your terminal will display something like:

╔══════════════════════════════════╗
║   ADRIEN-MD PAIRING CODE         ║
╠══════════════════════════════════╣
║                                  ║
║      🔑  ABCD-EFGH               ║
║                                  ║
║   Code expires in 60 seconds     ║
╚══════════════════════════════════╝

3️⃣ Link on WhatsApp

On your phone:

    Open WhatsApp ➜ tap the ⋮ menu (Android) or Settings (iOS)
    Tap Linked Devices ➜ Link a Device
    Tap Link with phone number instead
    Enter the 8-character code shown in your terminal

4️⃣ You're Connected! 🎉

✅ Connection established
✅ Session saved to ./auth/
✅ Adrien-MD is now online

    💡 Tip: Your session is stored locally in the auth/ folder. Back this folder up if you want to avoid re-pairing later.

🆔 Pairing Code via Web Panel

Adrien-MD also ships with a built-in web pairing panel — handy for cloud deployments:

npm run pair:web

Then open http://localhost:3000/pair in your browser, enter your number, and your code will appear instantly.
❗ Pairing Troubleshooting
	
	
	
	
	
	
🚀 Installation
⚙️ Prerequisites

    Node.js v20 or higher
    Git
    FFmpeg (for media processing)
    An active WhatsApp account

📦 Local Installation

# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/Adrien-MD.git
# 2. Move into the directory
cd Adrien-MD
# 3. Install dependencies
npm install
# 4. Configure environment
cp .env.example .env
nano .env
# 5. Start the bot
npm start

🔧 Environment Variables
Variable	Description	Default
PREFIX	Command prefix	.
OWNER_NUMBER	Your WhatsApp number	required
BOT_NAME	Display name of the bot	Adrien-MD
LANGUAGE	Default response language	en
MODE	public or private	public
PAIRING_NUMBER	Number to pair with	optional
AUTO_READ	Auto-mark messages as read	false
AUTO_REACT	Auto-react to messages	false
ANTI_DELETE	Recover deleted messages	true
📂 Project Structure

Adrien-MD/
├── 📁 assets/          # Images, fonts & media
├── 📁 auth/            # Saved sessions (auto-generated)
├── 📁 commands/        # Plugin-based command modules
│   ├── admin/
│   ├── downloader/
│   ├── fun/
│   ├── group/
│   └── owner/
├── 📁 lib/             # Core utilities & helpers
├── 📁 config/          # Bot configuration
├── 📁 database/        # Local DB & schemas
├── 📄 index.js         # Entry point
├── 📄 package.json
└── 📄 .env.example

🎯 Command Examples
Command	Description
.menu	Show full command list
.ping	Check bot latency
.sticker	Convert image/video to sticker
.play <song>	Download YouTube audio
.ai <prompt>	Chat with the AI assistant
.tagall	Mention everyone in a group
.kick @user	Remove a user from group
.antilink on	Enable anti-link protection
☁️ Deployment Options
Platform	One-Click Deploy
Heroku	
Unsupported image
Railway	
Unsupported image
Render	
Unsupported image
Koyeb	
Unsupported image
🛡️ Security & Privacy

    ✅ Sessions are stored locally — never transmitted
    ✅ Open-source code — audit anything you want
    ✅ No telemetry, no tracking
    ⚠️ Never share your auth/ folder or session ID publicly

🤝 Contributing

Contributions, issues, and feature requests are warmly welcomed!

    Fork the project
    Create your feature branch: git checkout -b feature/AmazingFeature
    Commit your changes: git commit -m 'Add some AmazingFeature'
    Push to the branch: git push origin feature/AmazingFeature
    Open a Pull Request

Please read CONTRIBUTING.md for our code of conduct and pull request process.
📜 License

Distributed under the MIT License. See LICENSE for more information.
⚠️ Disclaimer

    Adrien-MD is not affiliated with, endorsed by, or sponsored by WhatsApp Inc. or Meta. Misuse of this bot may result in your WhatsApp account being banned. Use responsibly — the developers assume no liability for misuse.

💬 Support & Community

Unsupported image
Unsupported image
Unsupported image
⭐ If Adrien-MD helped you, please consider starring the repo!

Made with ❤️ by Adrien

Powered by Baileys

