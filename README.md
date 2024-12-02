# AI Agents in LangGraph Course Notebooks

This repository contains Jupyter Notebooks and code that I am using as I progress through the "AI Agents in LangGraph" course offered by LangChain and Tavily. The notebooks explore various concepts and techniques related to building and controlling AI agents using the LangGraph framework.

**Course Information:**

*   **Title:** AI Agents in LangGraph
*   **Instructors:** Harrison Chase (LangChain), Rotem Weiss (Tavily)
*   **Platform:**  [Mention where you are taking the course, e.g., LangChain's website, YouTube, etc. If possible, add a link.]
*   **Focus:** Building controllable AI agents using the LangGraph framework, integrating agentic search, and implementing advanced features like persistence and human-in-the-loop.

**Purpose of this Repository:**

This repository serves as:

*   **A learning journal:** To document my progress, code implementations, and understanding of the course material.
*   **A personal reference:** To easily access and review the code examples and concepts covered in the course.
*   **A potential resource for others:**  (Optional) If you intend to share your work, you can add this line indicating that others might find it helpful.

**Repository Structure:**

The repository is organized to mirror the structure of the course:

*   `notebooks/`: Contains Jupyter Notebooks for each lesson or module of the course. Each notebook is named descriptively to indicate its content.
    *   Subfolders within `notebooks/` are used to group related notebooks if applicable (e.g., based on course sections).
*   `environment/`:
    *   `requirements.txt`: Lists the Python dependencies required to run the notebooks.
    *   `environment.yml`:  (Optional) If using conda, an environment file for reproducibility.
*   `data/`: (Optional)  If the course involves external datasets, they would be placed here.
*   `README.md`: This file you are currently reading!
*   `LICENSE`: (Optional)  If you're adding an open-source license, it will be here.
*   `.gitignore`:  Specifies files and directories that should not be tracked by Git (e.g., temporary files, API keys if stored in a `.env` file).

**Getting Started:**

1. **Clone the Repository:**

    ```bash
    git clone <your_repo_url>
    cd langgraph-course-notebooks
    ```

2. **Create and Activate a Virtual Environment (Recommended):**

    Using `venv` (Python's built-in virtual environment manager):

    ```bash
    python3 -m venv environment
    source environment/bin/activate  # On Linux/macOS
    # environment\Scripts\activate  # On Windows
    ```

    Or, if using `conda`:

    ```bash
    conda env create -f environment/environment.yml
    conda activate <your_env_name>
    ```

3. **Install Dependencies:**

    ```bash
    pip install -r environment/requirements.txt
    ```

4. **Set up API Keys (if applicable):**

    Some notebooks may require API keys for services like OpenAI or Tavily. **Do not store your API keys directly in the notebooks or the repository.** Instead:

    *   Store your keys securely as environment variables.
    *   This repository assumes the following environment variables are set:
        *   `OPENAI_API_KEY`: Your OpenAI API key.
        *   `TAVILY_API_KEY`: Your Tavily API key.
        *   Add other keys as needed.

    You can set them in your shell or use a `.env` file (if you're using a library like `python-dotenv` and have added `.env` to your `.gitignore`).

    Example:

    ```bash
    export OPENAI_API_KEY="your_openai_key_here"
    export TAVILY_API_KEY="your_tavily_key_here"
    # ...other keys
    ```

5. **Launch Jupyter Notebook:**

    ```bash
    jupyter notebook
    ```

    Then navigate to the `notebooks` directory and open the desired notebook.

**Note:**

*   This repository is a work in progress and will be updated as I progress through the course.
*   The code and explanations provided in the notebooks are based on my understanding of the course material and may contain errors or be subject to improvement.

**Feedback and Contributions:**

(Optional) If you decide to make your repo public and want to invite collaboration:

*   If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

**License:**

(Optional) If you add an open-source license, link to the license file here and briefly describe the terms. For example:

*   This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
