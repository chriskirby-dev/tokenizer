# Tokenizer

The Tokenizer module provides functionality for tokenizing and parsing templates in JavaScript. It is designed to efficiently process template files and replace tokens with corresponding values, enabling dynamic content generation.

## Features

- **Tokenization**: Breaks down templates into tokens for parsing.
- **Template Parsing**: Parses tokens within templates and replaces them with corresponding values.
- **Includes Support**: Handles inclusion of external template files within the main template.

## Installation

The Tokenizer module can be installed via npm:

```bash
npm install @example/tokenizer
```

## Usage
```javascript
import Tokenizer from "@example/tokenizer";

// Initialize a Tokenizer instance
const tokenizer = new Tokenizer(templateString, data, options);

// Render the template with provided data
const renderedTemplate = tokenizer.render();

console.log(renderedTemplate);
```
