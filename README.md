# TB Negative Keyword Script v2

A Google Ads script for MCC-level negative keyword management with AI integration. This script runs hourly in Google Ads and helps identify and manage poor-performing search terms based on rules set in a connected spreadsheet.

## Features

- Exports bad performing search terms based on configurable rules
- Fetches API key, prompt, and context from a connected spreadsheet
- Uses AI to categorize search terms into:
  - Irrelevant search terms
  - Relevant but poor-performing search terms
  - Other poor-performing search terms
- Works at both MCC and single account level
- Provides detailed performance metrics and analysis

## Files

- `neg_keyword_script_v2.js` - The main Google Ads script
- `prompt in spreadsheet.txt` - The prompt template used in the spreadsheet for AI analysis
- `context example spreadsheet.txt` - Example of how context is added in the spreadsheet

## Setup

1. Create a Google Ads script in your MCC account
2. Copy the contents of `neg_keyword_script_v2.js` into the script
3. Run the script once to generate a spreadsheet URL
4. Update the `MY_SHEET` constant in the script with your spreadsheet URL
5. Configure the settings in the spreadsheet
6. Schedule the script to run hourly

## Requirements

- Google Ads MCC account
- Access to Google Sheets
- API key for AI integration (if using AI features)

## Author

Traffic Builders - Pushing Marketing Boundaries