# Flutter Conferences Public Archive

**Live Website:** [https://happycode.studio/flutter_conferences_public/](https://happycode.studio/flutter_conferences_public/)

This repository serves as a public archive for various Flutter conferences from 2024 onwards. Our goal is to centralize conference schedule and talk data to make it easily accessible for community purposes such as organizing playlists, finding speakers, and historical reference.

This includes the generated visualization site and the raw JSON data files.

## Contributing

If you have JSON data for a new conference or updates to an existing one, please submit a Pull Request to this repository with your JSON files.

### How to add a new conference

1. **Format your data:** Ensure your conference data matches the expected JSON schema. You can check the existing files in the `data/` folder for reference. Name your file in the `YYYY_conference_name.json` format (e.g., `2025_flutter_example.json`).
2. **Place the file:** Add your new JSON file to the `data/` directory.
3. **Update the index:** Open the `data/index.json` file and add the name of your new file (without the `.json` extension) to the array, keeping the list in alphabetical order. For example, add `"2025_flutter_example"`.
4. **Submit a PR:** Commit your changes and submit a Pull Request to this repository! Once merged, the GitHub Pages viewer will automatically pick it up and display your data on the website.
