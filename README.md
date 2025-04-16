# <img src="public/icon.svg" alt="Calmify Icon" width="28" height="28" style="vertical-align: middle;"> Calmify

Calmify is a modern, customizable lofi music player built with Next.js and TypeScript. It’s perfect for coding, studying, or simply unwinding. Give it a try: [demo](https://Calmify.vercel.app/).

<p align="center">
  <img src="demo.gif" alt="Calmify Demo" width="800px" />
</p>

## ✨ Features

- 🎨 A stylish retro TV-inspired interface
- 🎬 Seamless YouTube integration for endless lofi streams
- 🎛️ Multiple sound effects to enhance your vibe
- 🌈 Theme customization options
- 📻 Easy channel management (add, edit, delete custom channels)
- 🎚️ Independent volume controls for music and sound effects
- 💾 Settings persist across sessions using localStorage
- 📱 Fully responsive design for all devices

## 🎵 Customization

### Add Your Own Channels

Make Calmify unique by adding your favorite lofi streams:

1. Click the '+' button in the channel list.
2. Paste the YouTube URL of any lofi stream.
3. Add a name, description, and creator information.
4. Save and enjoy your personalized channel!

Your custom channels are stored locally and persist between sessions.

### Mix Sound Effects

Create the perfect atmosphere by combining different ambient sounds:

- ☕ Café ambience
- ⌨️ Keyboard typing
- 🔥 Fireplace crackling
- 🌧️ Rain sounds
- 🌫️ White noise
- 🌪️ Wind sounds

To add your own sound effects:

1. Click the '+' button in the sound effects panel.
2. Enter a name for your effect.
3. Provide a YouTube URL for the sound file.
4. Adjust the volume to your liking.

Each sound effect has its own volume control, letting you mix them with your music. All custom effects are saved locally for your next session!

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Known Limitations

- **Mobile Volume Control**: Mobile browsers (Safari, Chrome on iOS, etc.) may not support programmatic volume control due to security restrictions. Users will need to adjust volume using their device’s physical buttons.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/aminexfrad/Calmify
cd Calmify
```

2. Install dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

3. Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to start enjoying the vibes! 🎧

### 🐳 Using Docker

You can also run Calmify with Docker:

```bash
# Build the Docker image
docker build -t Calmify .

# Run the container
docker run -p 3000:3000 Calmify
```

Visit [http://localhost:3000](http://localhost:3000) in your browser to start vibing! 🎧

### 🎮 Usage

- **Channel Navigation**: Switch between different lofi streams using the channel buttons.
- **Sound Effects**: Toggle ambient sounds (rain, cafe, typing, etc.) to customize your experience.
- **Volume Control**: Adjust the volume of both music and effects independently.
- **Custom Channels**: Add your favorite lofi YouTube streams.
- **Theme Customization**: Choose from various visual themes.

## 🛠️ Built With

- [Next.js](https://nextjs.org/) - React framework
- [TypeScript](https://www.typescriptlang.org/) - For type safety
- [Tailwind CSS](https://tailwindcss.com/) - For styling
- [Shadcn UI](https://ui.shadcn.com/) - For UI components
- [React Player](https://github.com/cookpete/react-player) - For YouTube playback

## 🤝 Contributing

We welcome contributions to improve this project! Here’s how you can contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- To all the wonderful lofi music creators
- The open-source community
- Coffee ☕ for keeping the productivity going