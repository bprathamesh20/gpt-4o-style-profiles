# GPT-4o Image Generation Style Profiles

This repository contains a curated collection of style profiles designed for use with GPT-4o’s image generation capabilities.

## What Are JSON Style Profiles?

JSON style profiles define specific visual styles and provide the image generation model with structured information to consistently replicate those styles across different prompts.

## How to Use

To use a style profile, simply include the relevant JSON along with your image prompt. Instruct the model to reference the style profile to guide the image generation process.

## Example prompt

```
Create image create an icon for a notes app the generates notes using ai , the icon conatains a note book with a sparkle on it.

reference the below style guide
{paste the json style profile}

```