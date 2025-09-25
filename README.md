# Toast Tables Call Transcript Analyzer

A simple workflow to analyze Toast Tables sales call transcripts using Zapier's native OpenAI integration.

## Overview

This project uses **Zapier's built-in OpenAI integration** to analyze call transcripts and automatically populate a Google Sheet with structured data. No hosting or deployment required!

## How It Works

1. **Google Form** collects transcript data (rep name, restaurant name, transcript)
2. **Zapier** triggers on form submission
3. **OpenAI** analyzes the transcript using our custom prompt
4. **Google Sheets** receives the structured CSV data

## Setup

Follow the detailed instructions in `ZAPIER_NATIVE_SETUP.md` to configure your Zapier workflow.

## Files

- `ZAPIER_NATIVE_SETUP.md` - Complete setup guide
- `api-keys.env` - API keys storage (not committed to Git)
- `.gitignore` - Git ignore rules

## Benefits

- ✅ No hosting required
- ✅ No deployment complexity
- ✅ Uses Zapier's reliable infrastructure
- ✅ Easy to modify and maintain
- ✅ Built-in error handling
- ✅ Visual workflow management

## Google Form

Your form is ready at: https://docs.google.com/spreadsheets/d/1hoY6J90BvuP04cLHFgkfWe5wf0YKcl8-5J9TjVEN_2g/edit

## Google Sheet

Your analysis results will appear in your existing sheet: https://docs.google.com/spreadsheets/d/1Bi0lHazi9JKI_AP-UzVZLReZ_AVztckMEGZAFW0hfPQ/edit