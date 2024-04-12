# Rust OpenAI Chat Interface

This repository contains a Rust application that facilitates real-time chatting with OpenAI's GPT model. The application reads the API key from the environment, allows the user to send messages, and receives responses directly from OpenAI.

## About the Project

This Rust project utilizes the `openai_api_rust` crate to create an interactive chat application that communicates with OpenAI's API. Users can engage in a conversational exchange with OpenAI's AI models directly from the command line.

## Getting Started

To get this application running on your local machine, follow these steps:

```bash
# Clone the Repository
git clone https://github.com/yourusername/rust-openai-chat.git

# Navigate to the Project Directory
cd rust-openai-chat

# Set up Environment Variable
# Make sure to export your OpenAI API key as an environment variable:
export OPENAI_API_KEY='your_openai_api_key'

# Build the Project
# Use Cargo, Rust's build system and package manager:
cargo build --release

# Run the Application
# Start the chat interface:
cargo run --release

# Chat with OpenAI
# Once running, the application will prompt you to enter text. Type your message and see the response from OpenAI. Type 'quit' to exit the chat.
```

## Features

- **Real-time Chatting**: Engage in a real-time chat with OpenAI's AI.
- **Environment Variable Configuration**: Securely load your OpenAI API key from environment variables.
- **Error Handling**: Robust error handling to ensure smooth interaction even when API calls fail.

## Technologies Used

- Rust
- `openai_api_rust` crate
- OpenAI API

## License

This project is licensed under the Zero-Clause BSD License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the OpenAI team for providing the API and documentation that made this project possible.
- Thanks to the Rust community for excellent resources and support.

For any queries or further information, feel free to contact me through GitHub or my professional email linked in my portfolio.
```
