# Quorum

A simple, client-side web application for managing and tracking votes in real-time. Perfect for homeowner associations, club elections, committee meetings, or any group decision-making process.

## Features

- **Create Voting Groups**: Set up multiple voting groups with custom titles
- **Manage Voters**: Add voters with individual names and voting power (vote count)
- **Record Votes**: Track "Yeah", "Nay", and "Present" votes in real-time
- **Vote Tallying**: Automatically calculate and display vote totals
- **Persistent Storage**: Save voting data in your browser's local storage
- **Drag-and-Drop Reordering**: Easily reorder voters with intuitive drag-and-drop functionality
- **Two Sharing Modes**:
  - **Configuration Sharing**: Generate shareable links to distribute voting configurations
  - **Real-time Collaborative Voting**: Create live voting sessions where multiple participants can see votes as they're cast
- **Peer-to-Peer Communication**: Connect multiple devices for synchronized voting without a central server
- **Responsive Design**: Works on desktop and mobile devices
- **No Server Required**: Runs entirely in the browser with no backend dependencies

## How It Works

### Basic Usage

1. **Create a Voting Group**: Enter a title for your voting session
2. **Add Voters**: Click "Add Voter" to add participants, specifying their name and voting power
3. **Arrange Voters**: Drag and drop voters to reorder them as needed (in edit mode)
4. **Save Configuration**: Click the pencil icon to toggle between edit and voting modes
5. **Record Votes**: Click the colored buttons (Yeah, Present, Nay) to record each voter's position
6. **View Results**: See vote totals at the bottom of the screen

### Sharing Options

#### Share Configuration (Static)
1. In edit mode, click the document icon in the header
2. A shareable link will be copied to your clipboard
3. Send this link to others to share your voter configuration

#### Create Voting Session (Real-time)
1. In voting mode (not edit mode), click the broadcast icon in the header
2. A voting session link will be copied to your clipboard
3. Share this link with participants to start a collaborative voting session
4. All connected peers will see votes in real-time as they are cast
5. The number of connected peers is displayed in the header
6. Only the session creator can edit voters (add, remove, or modify)

## Technical Details

**Quorum** is built with:
- HTML5
- CSS3
- JavaScript
- [Alpine.js](https://alpinejs.dev/) for reactivity and state management
- [PeerJS](https://peerjs.com/) for WebRTC peer-to-peer communication
- LocalStorage API for data persistence

The application runs entirely in the browser and doesn't require any server-side components or databases. All data is stored locally in the user's browser, and real-time communication happens directly between peers using WebRTC technology.

## Getting Started

Simply open the `index.html` file in a web browser or host the files on any web server.

```bash
# If you have Python installed, you can quickly start a local server with:
python -m http.server

# Then open http://localhost:8000 in your browser
```

## Privacy

Quorum respects your privacy:
- No data is sent to any server (except for WebRTC signaling)
- All voting information is stored locally in your browser
- Peer-to-peer connections are direct between browsers
- No cookies or tracking scripts are used

## License

This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.

## Support

If you enjoy using this app, consider supporting the developer:

[![Buy Me A Coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://buymeacoffee.com/holzschneider)
