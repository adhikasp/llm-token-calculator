# LLM Token Calculator

A simple web-based calculator to estimate token count and costs for various LLM models. Access it at [https://adhikasp.github.io/llm-token-calculator/](https://adhikasp.github.io/llm-token-calculator/)

## Features

- Estimates token count for input text
- Calculates input and output costs based on model pricing
- Supports multiple models:
  - GPT-4o
  - GPT-4o-mini 
  - O1
  - O1-mini
- Shows warnings when approaching model context window limits
- Real-time calculation as you type

## Usage

1. Select your desired model from the dropdown
2. Enter or paste your text in the text area
3. View the estimated:
   - Token count
   - Input cost
   - Output cost 
   - Total cost

The calculator uses a conservative estimation approach based on text length to approximate token count.

## Technical Details

- Built with vanilla HTML, CSS, and JavaScript
- No external dependencies
- Responsive design that works on mobile and desktop
- Uses approximate token counting based on character length with safety margins
