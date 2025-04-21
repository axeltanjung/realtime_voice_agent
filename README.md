# Real-Time RAG Voice Agent

Powered by **Cartesia**, this project leverages real-time Retrieval-Augmented Generation (RAG) to create an intelligent voice agent.

## Features
- **Real-Time Responses**: Delivers instant, accurate answers.
- **Voice Interaction**: Seamless voice-based communication.
- **Powered by Cartesia**: Advanced AI-driven capabilities.

## Requirements
- Cartesia AI key
- OpenAI API key
- LiveKit credentials

## Setup
- Copy .env.example to .env
- Configure the following environment variables:

```
    OPENAI_API_KEY=your_openai_api_key
    CARTESIA_API_KEY=your_cartesia_api_key
    LIVEKIT_URL=your_livekit_url
    LIVEKIT_API_KEY=your_livekit_api_key
    LIVEKIT_API_SECRET=your_livekit_api_secret
```


## Getting Started
1. Clone the repository:
    ```bash
    git clone https://github.com/axeltanjung/realtime_voice_agent.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the application:
    ```bash
    python app.py
    ```

## License
This project is licensed under the [MIT License](LICENSE).

## Contributing
Contributions are welcome! Please see the [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.
