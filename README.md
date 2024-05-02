# Technical-Writer

## Overview
Technical-Writer automates the updating of README files in response to code changes. Triggered by merged PRs, it leverages OpenAI's API for content generation and LangChain for orchestrating the automation process.

## Features
- Automates README updates upon PR merges using AI.
- Utilizes GitHub Actions for workflow automation.
- Integrates with LangChain to manage AI interactions and logic flow.
- Employs OpenAI's API for context-aware content generation.

## Current Status
This project is in the early stages of development. Further instructions will be provided as the implementation progresses.

## Contributing
Contributions are welcome. Please submit any issues or pull requests through GitHub.

## License
This project is released under the MIT License. See the `LICENSE` file for more details.

## Acknowledgements
- OpenAI for providing the API used for generating content.
- GitHub for hosting and automation capabilities.
- LangChain for the automation framework used to streamline AI operations.
- Added cffi==1.16.0, cryptography==42.0.5, Deprecated==1.2.14, PyGithub==2.3.0, PyJWT==2.8.0, PyNaCl==1.5.0, and wrapt==1.16.0 to requirements.txt
- Changed github import back to the way it was