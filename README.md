# Voice Assistant using Python

This project demonstrates how to build a simple voice assistant using Python in a Jupyter Notebook environment. The assistant can recognize text commands (typed as input), respond with speech (or print if speech is not supported), and perform simple actions like searching Wikipedia, opening websites, telling jokes, and reporting the current time.

## Features

- Greets the user according to the time of day
- Recognizes and processes user commands (typed, not spoken in Colab)
- Searches Wikipedia and summarizes results
- Opens YouTube or Google in a web browser
- Tells the current system time
- Tells a random programming joke
- Gracefully exits on command

## Tools & Libraries Used

- **Jupyter Notebook**: Interactive development and demonstration
- **SpeechRecognition**: (Listed as dependency, but not used for voice input in Colab)
- **pyttsx3**: Text-to-speech (with print fallback for Colab)
- **wikipedia**: To fetch and summarize Wikipedia articles
- **pyjokes**: For programming jokes
- **Standard Python libraries**: `datetime`, `webbrowser`, `os`

## Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook or JupyterLab

### Installation

Clone the repository:
```bash
git clone https://github.com/utkarsh884/Voice-Assistant-using-python.git
cd Voice-Assistant-using-python
```

Install dependencies (directly from the notebook, or manually):
```bash
pip install SpeechRecognition pyttsx3 wikipedia pyjokes
```

### Usage

1. Start Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Open `Voice_Assistant_using_python.ipynb` and run the cells in order.
3. Type your commands when prompted (speech input is not supported in Colab).

#### Example Commands

- `open wikipedia python programming`
- `open youtube`
- `open google`
- `what time is it`
- `tell me a joke`
- `bye`

## Project Structure

- `Voice_Assistant_using_python.ipynb` – Main notebook with all code and instructions
- `README.md` – Project documentation

## Limitations

- Voice input is not supported in Colab; user must type commands.
- For text-to-speech, if running in Colab or a restricted environment, output will fall back to text.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or bug fixes.

## License

No license specified. If you wish to use or distribute this project, please contact the repository owner.

## Contact

For questions or suggestions, please open an issue or contact [utkarsh884](https://github.com/utkarsh884).
