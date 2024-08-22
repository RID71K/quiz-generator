# Interactive Quiz Generator with Streamlit

This project is an interactive quiz generator built with Streamlit, designed to automate the creation of quizzes from PDF documents. It leverages document processing, embedding generation, and Chroma collections to facilitate an engaging and user-friendly quiz experience.

## Features

- **Automated Document Processing:** Ingests and processes PDFs to extract text.
- **Dynamic Quiz Generation:** Allows users to specify quiz topics and the number of questions.
- **Interactive Quiz Interface:** Provides real-time feedback and navigation through quiz questions.
- **State Management:** Maintains user progress and interactions using `st.session_state`.

## How It Works

1. **Document Ingestion:** Upload PDF documents for processing.
2. **Embedding Generation:** Generates text embeddings for quiz creation.
3. **Quiz Generation:** Users specify the topic and number of questions.
4. **Quiz Interaction:** Users navigate and interact with quiz questions.

## Getting Started

### Prerequisites

- [Streamlit](https://streamlit.io/) - Python library for building interactive web apps.
- Python 3.x installed on your machine.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/quiz-generator.git
    cd quiz-generator
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

## Usage

1. Launch the app by running `streamlit run app.py` in your terminal.
2. Upload a PDF document to the app.
3. Specify the topic and number of questions for your quiz.
4. Generate and interact with your quiz!

## File Structure

- `app.py`: Main Streamlit application file.
- `tasks/`: Directory containing task-specific modules like document processing, embedding generation, etc.
- `requirements.txt`: File listing all dependencies required for the project.

## Contributing

We welcome contributions! Please fork the repository and submit a pull request for any improvements or additions.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Special thanks to the Streamlit community for their support and resources.

