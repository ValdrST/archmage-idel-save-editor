# Archmage Idle Save Editor

A static website for decoding an **Archmage Idle** save, viewing and editing its JSON fields, and downloading the modified save in AT1 format.

## Usage

1. Open the website published with GitHub Pages.
2. Select **Open save** or drag the save file onto the page. AT1 saves and plain JSON files are supported.
3. Edit the JSON in the text area.
4. Once the JSON is valid, select **Download encoded save**.

Files are processed locally in your browser; the website does not upload them to a server.

## Formats

- Input: AT1 exports or plain JSON saves.
- Output: AT1 exports with the `AT1:` prefix.
- Saves with compact keys are expanded to regular JSON when loaded.

Keep a backup of your original save before editing it.
