# AI Marketing Content Generator

An AI-powered web application that generates SEO-optimized English product titles and descriptions for Asian products targeting the US market. Built with Flask and OpenAI's GPT-4.

## Features

- **AI-Powered Title Generation**: Automatically translates and optimizes product titles for English-speaking audiences
- **Smart Description Creation**: Generates compelling product descriptions with key selling points
- **SEO Optimization**: Incorporates relevant keywords while avoiding problematic terms
- **Quality Scoring**: Rates generated content on a 1-10 scale with visual feedback
- **Batch Processing**: Handle multiple products at once
- **Easy Export**: One-click copy functionality for quick integration

## Screenshots

![Title Generator Interface](https://via.placeholder.com/800x400.png?text=Title+Generator+Interface)
*Generate SEO-optimized product titles with quality scoring*

![Description Generator Interface](https://via.placeholder.com/800x400.png?text=Description+Generator+Interface)
*Create compelling product descriptions with key highlights*

## Technology Stack

- **Backend**: Python 3.11, Flask
- **AI**: OpenAI GPT-4 API
- **Frontend**: HTML5, Bootstrap 4, jQuery
- **Deployment**: Heroku-ready with Gunicorn

## Prerequisites

- Python 3.11+
- OpenAI API key
- pip (Python package manager)

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/kenku0/ai-marketingcontent-generator.git
   cd ai-marketingcontent-generator
   ```

2. **Create a virtual environment**
   ```bash
   python3 -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**
   ```bash
   cp .env.example .env
   # Edit .env and add your OpenAI API key
   ```

## Usage

1. **Start the application**
   ```bash
   python app.py
   ```

2. **Open your browser**
   Navigate to `http://localhost:5000`

3. **Generate content**
   - **Title Generation**: Enter product names in the left panel, click "Generate Titles"
   - **Description Generation**: Switch to the Description tab, enter product details, click "Generate Descriptions"

## API Configuration

The application requires an OpenAI API key. Set it as an environment variable:

```bash
export OPENAI_API_KEY='your-api-key-here'
```

Or add it to your `.env` file:
```
OPENAI_API_KEY=your-api-key-here
```

## Use Cases

- **E-commerce Sellers**: Quickly create English listings for Asian products
- **Marketing Teams**: Generate consistent, SEO-friendly product content
- **Content Creators**: Streamline product description workflows
- **International Businesses**: Bridge language gaps in product marketing

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built for the Yami marketplace ecosystem
- Powered by OpenAI's GPT-4
- Bootstrap for responsive UI components

## Contact

Project Link: [https://github.com/kenku0/ai-marketingcontent-generator](https://github.com/kenku0/ai-marketingcontent-generator)

---

Made with love for better product localization