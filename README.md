# Smol Vision - Image Analysis Notebook

This notebook, **Smol Vision**, is designed to automatically analyze images using an AI-powered workflow only using locally hosted open source models via Ollama.

### What's Inside?

- **Installation**: Install necessary packages with `pip install langgraph langchain_ollama langchain ollama`.
- **Moondream2**: Given an image, we describe it using Moondream2.
- **Llama 3.1 8B**: We use Llama 3.1 8B to structure the image description.
- **Data Extraction**: We break down the image description into structured data (title, subject, colors, setting).

### Workflow:
1. **generate_description**: Creates a description of the image using Moondream2.
2. **extract_data**: Extracts structured data from the description using Llama 3.1 8B.
3. **Output**: Displays the creative title, subject, colors, and setting.

### Example

With an image like `sweat_suit_cat.jpeg`:
<br>
<br>
<img src="sweat_suit_cat.jpeg" alt="sweat_suit_cat.jpeg" width="400"/>
<br>
<br>
You get:
- **Creative Title**: Whiskers on the Move
- **Subject**: Cat
- **Colors**: Gray, Brown
- **Setting**: City Street

Feel free to clone, customize, and enjoy exploring image descriptions and structured outputs!
