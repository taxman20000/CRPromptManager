# CRPromptManager

A powerful Python library for creating and managing AI chat prompts with a user-friendly GUI interface. Part of the ChatRecall project.

## Features

- **Intuitive GUI Interface**: Create, edit, and manage AI prompts with ease
- **Prompt Templates**: Save and reuse your favorite prompt configurations
- **Placeholder Support**: Insert dynamic content into your prompts
- **Output Formatting**: Control how AI responses are formatted
- **Backup System**: Automatic backup of your prompts and settings
- **Cross-Platform**: Works on Windows, macOS, and Linux

## Installation

```bash
# Clone the repository
git clone https://github.com/ChatRecall/CRPromptManager.git
cd CRPromptManager

# Install dependencies
pip install -e .
```

### Dependencies

This project relies on several WrapTools packages:
- [WrapAI](https://github.com/WrapTools/WrapAI) (required)
- [WrapCapPDF](https://github.com/WrapTools/WrapCapPDF) (optional, for PDF functionality)
- [WrapDataclass](https://github.com/WrapTools/WrapDataclass) (required)
- [WrapSideSix](https://github.com/WrapTools/WrapSideSix) (required)

To install these dependencies:
```bash
# Clone and install each dependency
git clone https://github.com/WrapTools/WrapAI.git
cd WrapAI && pip install -e . && cd ..

git clone https://github.com/WrapTools/WrapDataclass.git
cd WrapDataclass && pip install -e . && cd ..

git clone https://github.com/WrapTools/WrapSideSix.git
cd WrapSideSix && pip install -e . && cd ..

# Optional for PDF functionality
git clone https://github.com/WrapTools/WrapCapPDF.git
cd WrapCapPDF && pip install -e . && cd ..
```

## Quick Start

```python
from crpromptmanager import main

# Launch the CRPromptManager GUI
main.run()
```

## Usage Examples

### Basic Usage

1. Launch the application
2. Create a new prompt or select an existing template
3. Configure your prompt settings
4. Run the prompt to get AI-generated responses


## Core Components

- **Prompt Runner**: Handles the execution of prompts with AI models
- **Settings Manager**: Configure and save your preferred settings
- **Placeholder System**: Insert dynamic content like dates, variables, or file contents
- **Output Formatter**: Control how AI responses are formatted and displayed
- **Backup System**: Automatically backs up your prompts and settings

## Requirements

- Python 3.9+
- PySide6 for the GUI components
- Internet connection for AI model access

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (```git checkout -b feature/amazing-feature```)
3. Commit your changes (```git commit -m 'Add some amazing feature'```)
4. Push to the branch (```git push origin feature/amazing-feature```)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Related Projects

This tool is part of the [ChatRecall](https://github.com/ChatRecall) project and works with the [WrapTools](https://github.com/WrapTools) ecosystem.

