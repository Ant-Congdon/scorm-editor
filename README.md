# SCORM Content Editor for Rise Courses

A simple browser-based tool for editing encoded SCORM content from Articulate Rise courses. This tool allows you to decode, edit, and re-encode the course content while preserving the original file structure.

## Features

- Decode Base64-encoded course content
- Edit course content in a readable JSON format
- Re-encode and save changes while maintaining file integrity
- Browser-based - no installation required
- Works offline
- Preserves original file structure and resources

## How to Use

1. Download `scorm-editor.html` to your local machine
2. Open `scorm-editor.html` in your web browser
3. Extract your SCORM Package and navigate to the scormcontent folder
4. Click "Choose File" and select your Rise course's `index.html` from the scormcontent folder
5. Click "Decode Content" to view the editable content in JSON format
6. Make your desired changes in the decoded text area
7. Click "Encode Content" to prepare your changes
8. Click "Save Changes" to download the new index.html file
9. Replace the original index.html in your scormcontent folder with the new file

## Important Notes

- Always make a backup of your original files before making any changes
- Test the modified course thoroughly before deploying
- The tool works entirely in your browser - no data is sent to any server
- Compatible with modern browsers (Chrome, Firefox, Edge, Safari)

## Safety Measures

- Original file structure is preserved
- Only the course content is modified
- All scripts and resources remain intact

## Limitations

- This tool only modifies the course content
- It's not pretty in terms of editing, changing a sentence or word here or there is ok, but not much nore
- Cannot modify the Rise player functionality
- Cannot add new features to the course
- Cannot modify locked or protected content

## Technical Details

The tool:
- Uses Base64 encoding/decoding
- Handles JSON parsing and stringifying
- Preserves original file structure
- Works with standard Rise SCORM output

## Contributing

Feel free to submit issues and enhancement requests.

## License

This project is licensed under a Creative Commons license.

## Disclaimer

This is an unofficial tool and is not affiliated with or endorsed by Articulate. Use at your own risk. Always backup your files before making any changes.
