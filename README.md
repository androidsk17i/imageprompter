# Photorealistic Prompt Generator

A powerful web-based tool that helps you create highly detailed, structured prompts for photorealistic AI image generation. Perfect for use with Midjourney, DALL-E, Stable Diffusion, and other AI image generation platforms.

![Photorealistic Prompt Generator](https://i.imgur.com/FZQnMKl.png)

## 🌟 Features

- **Structured Prompt Building**: Create well-formatted prompts with specific sections for subjects, environments, composition, lighting, and technical details
- **Photorealism Focus**: Optimized for generating realistic photographs rather than illustrations or CGI
- **Dark/Light Mode**: Comfortable interface for any lighting condition
- **Randomization**: Generate unlimited creative combinations with a single click
- **Individual Field Randomization**: Fine-tune specific aspects of your prompt
- **Preset Management**: Save and load your favorite prompt combinations
- **Auto-Copy**: Instantly copy prompts to your clipboard
- **Separate Negative Prompts**: Manage positive and negative prompts independently
- **Responsive Design**: Works on desktop and mobile devices

## 🚀 Quick Start

1. Visit the [Photorealistic Prompt Generator](https://yourusername.github.io/photo-prompt-generator/) (replace with your actual GitHub Pages URL)
2. Fill in the subject field (required)
3. Add details to other fields or use the "Randomize All" button
4. Copy the generated prompt with one click
5. Paste into your AI image generator of choice

Alternatively, you can:

1. Clone this repository
2. Open `index.html` in any modern browser
3. No build process or dependencies required!

## 💡 How to Use

### Creating Prompts

1. **Subject**: Start with a clear description of your main subject
2. **Environment & Mood**: Describe the setting and emotional tone
3. **Composition & Framing**: Add details about camera angles and composition
4. **Lighting & Color**: Specify lighting conditions and color schemes
5. **Camera & Technical Specs**: Include camera models and technical details
6. **Style & Quality Keywords**: Add finishing touches on the overall style
7. **Negative Prompts**: Specify what you don't want in your image

### Tips for Best Results

- **Be Specific**: "A serene lake surrounded by autumn trees" works better than just "a lake"
- **Use Quality Keywords**: Terms like "photorealistic", "highly detailed" help achieve better quality
- **Balance Detail**: Too little detail gives generic results, too much can confuse the AI
- **Use Negative Prompts**: Effectively filter out unwanted elements like "cartoon, anime, illustration"
- **Save Good Presets**: When you find a combination that works well, save it for later use

## 🔧 Customization

The Photorealistic Prompt Generator is built with vanilla HTML, Tailwind CSS, and JavaScript. You can easily customize it:

- **Add More Variations**: Extend the `variations` object in the JavaScript to add more options
- **Modify Default Negatives**: Change the `baseNegativePrompts` constant to match your preferences
- **Visual Styling**: Adjust the Tailwind classes or add custom CSS

## 💻 Technical Details

- **No Dependencies**: Pure HTML, CSS, and JavaScript
- **Lightweight**: Fast loading with minimal overhead
- **Local Storage**: Saves presets to your browser's local storage
- **No Server Requirements**: Works completely client-side
- **Tailwind CSS**: Styling via Tailwind CDN
- **Font Awesome**: Icons via Font Awesome CDN

## 📚 Prompt Structure

The generator creates prompts in this format:

```
[Subject]; [Environment & Mood]; [Composition & Framing]; [Lighting & Color]; [Camera & Technical Specs]; [Style & Quality Keywords]
```

Negative prompts are kept separate as some AI platforms have dedicated negative prompt fields.

## 🚀 Future Updates

Here's what's planned for upcoming versions:

- **Prompt History**: Save your generation history for easy reference
- **AI Model-Specific Templates**: Optimized presets for different AI models (Midjourney, DALL-E, Stable Diffusion)
- **Image Preview Integration**: Preview your prompt using integrated API connections
- **Advanced Randomization**: Weighted randomization to prioritize certain styles
- **Prompt Analysis**: Get suggestions to improve your prompt's effectiveness
- **Export/Import Configuration**: Share your variations and presets with others
- **Multi-Language Support**: Use the tool in your preferred language
- **Community Presets**: Browse and use presets shared by other users
- **Mobile App**: Native mobile application for iOS and Android

Have suggestions for future features? Open an issue or submit a pull request!

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 👏 Acknowledgements

- Built with [Tailwind CSS](https://tailwindcss.com/)
- Icons from [Font Awesome](https://fontawesome.com/)
- Inspired by best practices in AI image prompting

---

Made with ❤️ for the AI image generation community 