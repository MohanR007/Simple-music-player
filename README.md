# Music Player

This is a simple and elegant music player web application. It allows you to play, pause, skip tracks, adjust volume, and more. The design is responsive and looks great on all devices.

![Music Player](music-player-screenshot.png)

## Features

- Play and pause tracks
- Skip to the next or previous track
- Adjust volume
- Seek through the track
- Shuffle and repeat tracks
- Display current track details

## Technologies Used

- HTML
- CSS
- JavaScript
- Font Awesome

## How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/music-player.git
    ```
2. Open the `index.html` file in your web browser.

## How to Edit the Songs List

1. Open the `script.js` file in your preferred code editor.
2. Locate the section where the songs list is defined. It should look something like this:
    ```javascript
    let track_list = [
        {
            name: "Track 1",
            artist: "Artist 1",
            image: "path/to/image1.jpg",
            path: "path/to/song1.mp3"
        },
        {
            name: "Track 2",
            artist: "Artist 2",
            image: "path/to/image2.jpg",
            path: "path/to/song2.mp3"
        },
        // ...existing code...
    ];
    ```
3. Add or remove songs by modifying the `track_list` array. Each song should have a `name`, `artist`, `image`, and `path`.


