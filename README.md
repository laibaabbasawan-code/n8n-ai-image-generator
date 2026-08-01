# n8n-ai-image-generator
An n8n workflow that generates AI images from user prompts using the Pollinations API and stores prompts in a MySQL database.
# n8n AI Image Generator

## Overview

This project is an AI Image Generator workflow built using n8n.

Users submit an image prompt through an n8n Form Submission Trigger. The prompt is sent to the Pollinations AI Image API using an HTTP Request node to generate an AI image. The submitted prompt is then stored in a MySQL database for future reference.

## Workflow

Form Submission Trigger
        ↓
Edit Fields
        ↓
HTTP Request (Pollinations AI)
        ↓
MySQL Database

## Features

- User-friendly form submission
- Dynamic image prompt input
- AI image generation using Pollinations API
- Prompt storage in MySQL
- Low-code workflow automation using n8n

## Technologies Used

- n8n
- Pollinations AI API
- HTTP Request
- MySQL
- Form Submission Trigger

## How It Works

1. User opens the n8n form.
2. User enters an image prompt.
3. The workflow receives the prompt.
4. The HTTP Request node sends the prompt to Pollinations AI.
5. An AI-generated image is returned.
6. The prompt is saved in the MySQL database.

## Project Structure

Form Submission Trigger
        ↓
Edit Fields
        ↓
HTTP Request
        ↓
MySQL

## Future Improvements

- Store generated image URLs
- Download generated images automatically
- AI prompt enhancement using Gemini
- Image style selection
- Email generated images
- Image history dashboard

## Author

Laiba Abbas
