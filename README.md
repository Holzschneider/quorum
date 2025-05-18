# Quorum

A simple, client-side web application for managing and tracking votes in real-time. Perfect for homeowner associations, club elections, committee meetings, or any group decision-making process.

## Features

- **Create Voting Groups**: Set up multiple voting groups with custom titles
- **Manage Voters**: Add voters with individual names and voting power (vote count)
- **Record Votes**: Track "Yeah", "Nay", and "Present" votes in real-time
- **Vote Tallying**: Automatically calculate and display vote totals
- **Persistent Storage**: Save voting data in your browser's local storage
- **Sharing**: Generate shareable links to distribute voting configurations
- **Responsive Design**: Works on desktop and mobile devices
- **No Server Required**: Runs entirely in the browser with no backend dependencies

## How It Works

1. **Create a Voting Group**: Enter a title for your voting session
2. **Add Voters**: Click "Add Voter" to add participants, specifying their name and voting power
3. **Record Votes**: Click the colored buttons (Yeah, Present, Nay) to record each voter's position
4. **View Results**: See vote totals at the bottom of the screen
5. **Share**: Generate a link to share your voting configuration with others

## Technical Details

MeA-Rechner is built with:
- HTML5
- CSS3
- JavaScript
- [Alpine.js](https://alpinejs.dev/) for reactivity and state management
- LocalStorage API for data persistence

The application runs entirely in the browser and doesn't require any server-side components or databases. All data is stored locally in the user's browser.

## Getting Started

Simply open the `index.html` file in a web browser or host the files on any web server.

```bash
# If you have Python installed, you can quickly start a local server with:
python -m http.server

# Then open http://localhost:8000 in your browser
```

## Privacy

MeA-Rechner respects your privacy:
- No data is sent to any server
- All information is stored locally in your browser
- No cookies or tracking scripts are used

## License

This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.

## Support

If you enjoy using this app, consider supporting the developer:

[![Buy Me A Coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://buymeacoffee.com/holzschneider)