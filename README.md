# Halftone Gesture Control

An interactive visual experience that combines webcam input with hand gesture recognition to create a dynamic halftone dot pattern effect.

## Features

- **Real-time Video Processing**: Converts webcam feed into animated halftone dots
- **Hand Gesture Control**:
  - **Left Hand (Pinch)**: Adjust dot size by pinching thumb and index finger together/apart
  - **Right Hand (Swipe)**: Change colors by swiping in any direction
- **Motion Detection**: Movement creates ripple effects across the canvas
- **12 Vibrant Colors**: Cycle through a rainbow of high-saturation colors

## How to Use

1. Open `index.html` in a modern web browser (Chrome, Firefox, or Edge recommended)
2. Allow camera permissions when prompted
3. Click anywhere to enter fullscreen mode
4. Use your hands to control the visual effects:
   - Show your **left hand** to the camera and pinch to resize dots
   - Show your **right hand** and swipe to change colors

## Technical Details

- **Hand Tracking**: MediaPipe Hands library for accurate gesture recognition
- **Canvas Rendering**: High-performance 2D canvas animations
- **Motion Detection**: Frame difference analysis for interactive ripples

## Browser Requirements

- Modern browser with WebRTC support (camera access)
- JavaScript enabled
- Recommended: Desktop/laptop with webcam for best experience

## Controls

- **Left Hand Pinch**: Increase/decrease dot size (4-20px range)
- **Right Hand Swipe**:
  - Horizontal swipes: Navigate through colors sequentially
  - Vertical swipes: Jump 3 colors forward/backward
- **Click**: Toggle fullscreen mode

## Colors Available

Red → Orange → Yellow → Lime → Green → Spring Green → Cyan → Azure → Blue → Violet → Magenta → Rose

## Privacy

All processing happens locally in your browser. No data is sent to external servers.
