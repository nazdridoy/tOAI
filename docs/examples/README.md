# Code Examples

This directory contains comprehensive examples demonstrating how to use nGPT in various scenarios. These examples showcase both the library's API and the command-line interface.

## Table of Contents

- [Basic Examples](basic.md) - Simple examples to get started with nGPT
- [Advanced Examples](advanced.md) - More complex examples with advanced features
- [Custom Integrations](integrations.md) - Examples of integrating nGPT into larger applications

## Getting Started

To run these examples, you'll need to:

1. Install nGPT: `pip install ngpt`
2. Configure your API key: `ngpt --config` or set the `OPENAI_API_KEY` environment variable
3. Ensure you have the required dependencies for specific examples

## Example Categories

### Basic Examples

These examples demonstrate the fundamental functionality of nGPT:

- Simple chat interactions
- Code generation
- Shell command generation
- Basic configuration

### Advanced Examples

These examples show more sophisticated use of nGPT:

- Streaming responses
- Conversation management
- Working with multiple API providers
- Error handling and retries
- Custom system prompts

### Custom Integrations

These examples demonstrate how to integrate nGPT into larger applications:

- Web application integration
- Command-line tool development
- Chatbot development
- Workflow automation

## Quick Reference

Here's a quick reference to the most important examples:

```python
# Basic chat example
from ngpt import NGPTClient, load_config

config = load_config()
client = NGPTClient(**config)
response = client.chat("Tell me about quantum computing")
print(response)

# Code generation example
code = client.generate_code("function to calculate fibonacci numbers")
print(code)

# Shell command example
command = client.generate_shell_command("find all files modified in the last week")
print(command)
```

Explore the individual example pages for more detailed code samples and explanations. 