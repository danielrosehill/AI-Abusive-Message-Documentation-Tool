# AI Abusive Message Documentation Tool

## Overview

This repository contains system prompts designed to help individuals process and document emotionally abusive or manipulative messages without having to directly read the potentially triggering content. The tool creates an automated workflow where messages from abusive individuals undergo analysis and are then presented as a structured summary to the user.

## Purpose

Many individuals who receive hurtful and abusive messages from toxic people experience:
- Anxiety, trauma, and emotional distress when reading these communications
- A need to document these interactions for therapy, legal purposes, or personal records
- The risk of self-gaslighting over time, minimizing the severity of the abuse they've experienced

This tool serves as a buffer between the user and the original message, providing an objective record while protecting the user's mental health.

## How It Works

1. The user provides a message (email, text, screenshot, etc.) to an AI assistant configured with this system prompt
2. The AI analyzes the message without the user having to read it
3. The AI generates a structured report that includes:
   - Technical details (sender, timestamp, etc.)
   - Summary of content
   - Analysis of manipulative tactics
   - Optional quotes (with trigger warnings and whitespace)
   - The original message (separated by whitespace to avoid accidental viewing)

## Implementation

This tool can be implemented using:
- Any modern AI assistant (OpenAI's GPT models, Claude, etc.)
- Workflow automation tools like Zapier, Make, or N8n
- Custom applications with AI API integration

No advanced technical knowledge is required - the system works through simple text prompts that can be copied into any AI interface.

## Versions

This repository contains multiple versions of the system prompt:
- **Latest**: The most current version with improvements based on user feedback
- **Version History**: Previous iterations are maintained for reference

## Customization

The system prompt can be customized to meet individual needs:
- Adjust the level of detail in summaries
- Modify or remove the inclusion of direct quotes
- Change the format of the report
- Add specific instructions for particular types of abuse

## Important Notes

- **Not a Substitute for Professional Help**: This tool is designed as a supplementary aid and is not a replacement for professional mental health support
- **Privacy Considerations**: Be mindful of where and how you share sensitive messages
- **Compatibility**: Works with virtually any AI tool that accepts custom instructions

## Usage Example

1. Copy the system prompt from the `latest.md` file
2. Paste it into your preferred AI assistant's system prompt or instructions
3. Provide the message you want analyzed
4. Receive a structured report that protects you from direct exposure to the content

## License

This project is shared openly to help anyone dealing with abusive communications. You are free to use, modify, and share these prompts as needed.
 
