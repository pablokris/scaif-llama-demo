## Overview

This repository is part of the "Introducing Llama Index" demo, which can be found [here](https://bit.ly/3ItUEc9). It contains a very simple implementation that allows you to index the "paul_graham_essay.txt" and prompt questions. The demo is based on the official Llamaindex starter tutorial found [here](https://docs.llamaindex.ai/en/stable/getting_started/starter_example.html).

### Starter.py

This is the simplest implementation which will:

- Load the document
- Index it and create the vectors
- Answer the question

Note: In this implementation, the index is not persistent.

### Storing-your-index.py

This demo is the same as the starter, but will persist your index.

### Installation Documentation

Installation instructions can be found [here](https://docs.llamaindex.ai/en/stable/getting_started/installation.html).

#### Open AI Key Installation Steps:

- [ ] An OpenAI key is required to run this demo. Once you have created your key, follow the directions below to install it:
  1. Open Terminal: You can find it in the Applications folder or search for it using Spotlight (Command + Space).
  2. Edit Bash Profile: Use the command `nano ~/.bash_profile` or `nano ~/.zshrc` (for newer macOS versions) to open the profile file in a text editor.
  3. Add Environment Variable: In the editor, add the line below, replacing `your-api-key-here` with your actual API key:
     ```
     export OPENAI_API_KEY=your-api-key-here
     ```
  4. Save and Exit: Press `Ctrl+O` to write the changes, followed by `Ctrl+X` to close the editor.
  5. Load Your Profile: Use the command `source ~/.bash_profile` or `source ~/.zshrc` to load the updated profile.
  6. Verification: Verify the setup by typing `echo $OPENAI_API_KEY` in the terminal. It should display your API key.

### References

- [Llama Index Installation Instructions](https://docs.llamaindex.ai/en/stable/getting_started/installation.html)
- [Llama Index Quick Start](https://platform.openai.com/docs/quickstart?context=python)
- [Llama Index High Level Concepts](https://docs.llamaindex.ai/en/stable/getting_started/concepts.html)
- [Paul Graham File](https://raw.githubusercontent.com/run-llama/llama_index/main/docs/examples/data/paul_graham/paul_graham_essay.txt)
- [Llama Hub](https://llamahub.ai/)
- [Llama Index](https://www.llamaindex.ai/)
