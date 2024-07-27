# CamGPT 📸

CamGPT is a tool that allows you to chat with video using the OpenAI Vision API. Capture images using your webcam, send them along with prompts to the OpenAI API, and receive responses in a chat-like interface.

## Features

- Capture images using your webcam
- Send images and prompts to the OpenAI Vision API
- Receive and display responses in a chat interface
- Simple and intuitive UI built with Gradio

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/CamGPT.git
    cd CamGPT
    ```

2. Create a virtual environment and install dependencies:

    ```sh
    python3 -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ```

## Usage

1. Obtain your OpenAI API key from the [OpenAI website](https://beta.openai.com/signup/).

2. Run the application:

    ```sh
    python app.py
    ```

3. Open your web browser and go to `http://127.0.0.1:7860`.

4. Enter your OpenAI API key in the provided textbox.

5. Capture an image using your webcam, type a prompt, and hit enter to chat with the AI.


## Dependencies

- `base64`
- `os`
- `uuid`
- `cv2` (OpenCV)
- `gradio`
- `numpy`
- `requests`

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
