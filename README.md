# twitch.bot
🇬🇧 AI Twitch Companion (Autonomous Viewer)
This project is an experiment in creating a digital entity that doesn't just "read" chat logs—it actually watches the stream with you.

Most bots are blind text generators. This one is different. It acts as a full-fledged spectator that runs locally on your machine. It has "eyes" to see the gameplay moments, "ears" to hear the game audio, and it understands the vibe of the chat.

How it works conceptually:
Instead of waiting for commands, this AI sits in the background and consumes content just like a human viewer:

Visual Awareness: It constantly analyzes screenshots of the stream to understand what is happening on screen (e.g., "The player just won a match" or "The character is exploring a dark cave").

Audio Perception: It listens to the audio feed to catch context that might be missed visually.

Social Context: It reads the chat to stay in sync with the community's reaction.

By combining these senses using local Neural Networks (via Ollama) and Python, the bot generates relevant, context-aware comments and interacts with the streamer naturally, without any manual input.
