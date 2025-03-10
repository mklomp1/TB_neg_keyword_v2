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
- `neg_keyword_script_v2_fixed.js` - The fixed version of the script with improvements
- `prompt_in_spreadsheet.txt` - The prompt template used in the spreadsheet for AI analysis
- `context_example_spreadsheet.txt` - Example of how context is added in the spreadsheet

## Script Versions

### Original Version
The original script (`neg_keyword_script_v2.js`) provides the core functionality for negative keyword management in Google Ads.

### Fixed Version
The fixed version (`neg_keyword_script_v2_fixed.js`) includes several improvements:
- Enhanced JSON normalization for better AI integration
- Improved error handling
- Better performance with large datasets
- Fixed issues with data processing

**Note:** Due to GitHub API limitations, only a placeholder for the fixed script is included in this repository. The complete script (4059 lines) is available upon request.

## Setup

1. Create a Google Ads script in your MCC account
2. Copy the contents of the script into the script editor
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