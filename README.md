# Species Autocomplete for OMERO v2.0

## Overview
The **Species Autocomplete Extension** helps users autocomplete genus and species names on webpages, preventing misspellings and inconsistencies by referencing a preloaded list. The list is updated from a CSV file, which must contain only one column with taxa names and no header.

This extension was created to ensure consistent OMERO tags for palynological taxonomy.

⚠ **Currently, the extension ONLY supports Google Chrome and Chromium-based browsers like Microsoft Edge.**

## Features
- Works on any text input or textarea on any webpage (optimized for OMERO tags).
- Displays suggestions as you type.
- Allows selecting a suggestion by clicking it.
- Suggestions remain visible as you scroll.
- Limits to 15 suggestions at a time for performance optimization.
- Persists the species list across browser sessions.
- Can be activated or deactivated with a button.
- Allows selecting the CSV file separator.
- Displays the number of species loaded (excluding duplicates).
- Prioritizes the last species selected by the user.

## Installation
1. Open Chrome and go to `chrome://extensions/`.
2. Enable **Developer mode** (toggle in the top right corner).
3. Click **Load unpacked** and select the `species-autocomplete` folder.
4. The extension icon should now appear in your browser toolbar, indicating it is ready for use.

## Usage
1. Click the extension icon in your browser toolbar.
2. Select the separator of your CSV file.
3. Upload your species list (`.csv` file) with a single column of taxa names and no header.
4. The popup will display the number of species loaded and a preview of the parsed data.
5. Toggle the **Autocomplete** feature:
   - "Autocomplete **Inactive**" (red) → Click to activate.
   - "Autocomplete **Active**" (green) → Click to deactivate.
6. When active, the extension suggests species names based on the loaded data.

### Updating the Species List
- Upload a new CSV file and reload the extension.
- Verify the updated species count in the popup.

⚠ Ensure the necessary permissions are enabled for the extension to function correctly on the target webpages.

## Additional Notes
- **Privacy:** The extension does not store or transmit any personal data (it runs locally).
- **Icon Image:** A confocal microscopy image of *Grimsdalea magnaclavata* (Pollen Geo).
- **Permissions:** Requires access to local storage and specific webpages to enable autocomplete functionality.

## Version
- **v2.0**

## Author
- **David Caro**  
- 📧 [decaroc@unal.edu.co](mailto:decaroc@unal.edu.co)
