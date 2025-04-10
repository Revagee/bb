# Birthday Greetings Website

A beautiful website to display birthday greetings with videos from different people. The site features a modern design with animated confetti effects and responsive layout.

## Features

- Main page with greeting cards for different categories
- Individual pages for each person's video greeting
- Responsive design that works on all devices
- Beautiful animations and transitions
- Video player support

## Setup

1. Clone the repository:
```bash
git clone [your-repository-url]
```

2. Install dependencies:
```bash
npm install
```

3. Start the server:
```bash
node simple-server.js
```

4. Open your browser and visit:
```
http://localhost:3000
```

## Adding New Greetings

1. Place your video file in the `greetings` folder
2. Update the corresponding HTML file in the `greetings` folder
3. Make sure the video source path matches your video filename

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Node.js
- Express.js

## Structure

- `index.html` - Main page with greeting cards
- `greetings/` - Directory containing individual greeting pages and videos
- `simple-server.js` - Express server for hosting the website 