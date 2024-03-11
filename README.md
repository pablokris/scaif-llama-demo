## Overview

The following repo is a part of a "Introducing Llama Index" demo which can be found here: https://bit.ly/3ItUEc9

This repo contain a very simple implmentation based that allows you do index the "paul_graham_essay.txt" and prompt questions. The demo is based on the starter tutorial found here: https://docs.llamaindex.ai/en/stable/getting_started/starter_example.html

**Starter.py**

This is the simplest implementation which will...

- Load the document
- Index it and create the vectors
- Answer the question

Note: In this implementation, the index is not persistent

**Storing-your-index.py**

This demo is the same as starter, but will persist your index

**Installation Documentation**

https://docs.llamaindex.ai/en/stable/getting_started/installation.html

**Installation**

- [ ] An OpenAI key is required to run this demo. Once you created your
      key, below are the direction to install it

* [ ] Open Terminal: You can find it in the Applications folder or
      search for it using Spotlight (Command + Space).

* [ ] Edit Bash Profile: Use the command nano ~/.bash_profile or nano
      ~/.zshrc (for newer MacOS versions) to open the profile file in a
      text editor.

* [ ] Add Environment Variable: In the editor, add the line below,
      replacing your-api-key-here with your actual API key:

* [ ] Save and Exit: Press Ctrl+O to write the changes, followed by
      Ctrl+X to close the editor.

* [ ] Load Your Profile: Use the command source ~/.bash_profile or
      source ~/.zshrc to load the updated profile.

* [ ] Verification: Verify the setup by typing echo $OPENAI_API_KEY in
      the terminal. It should display your API key.

**References**

- Lllama index installation instructions: https://docs.llamaindex.ai/en/stable/getting_started/installation.html
- Llama Index Quick Start: https://platform.openai.com/docs/quickstart?context=python
- Llama index high level concepts: https://docs.llamaindex.ai/en/stable/getting_started/concepts.html

- Paul Graham file: https://raw.githubusercontent.com/run-llama/llama_index/main/docs/examples/data/paul_graham/paul_graham_essay.txt
- Llama hub: https://llamahub.ai/
- Llama index: https://www.llamaindex.ai/
