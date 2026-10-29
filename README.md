# EndlessDesktop

EndlessDesktop is a lightweight, infinite 2D spatial workspace for Windows. It transforms your desktop into a scalable canvas using native Windows DWM (Desktop Window Manager) thumbnails, allowing you to organize, zoom, and interact with your open windows in a completely new way.

## Features

- **Infinite Canvas:** Pan seamlessly across an endless 2D plane and zoom in or out.
- **Native Performance:** Utilizes Windows DWM for rendering live window previews, ensuring minimal CPU and GPU load.
- **Interactive Windows:** Click to focus and open real windows. Drag and resize them directly on the canvas.
- **Aspect Ratio Lock:** Windows maintain their original proportions (e.g., 16:9) when resized on the canvas.
- **Camera Fly-To:** Quickly focus on a specific window by selecting it and pressing `Space` to smoothly fly the camera to it.
- **Customization:** Built-in support for custom wallpapers, slideshow mode, dark/light themes, and grid toggling.
- **State Persistence:** The application automatically saves your layout, window positions, zoom level, and settings (e.g., selected wallpaper) between sessions.

## System Requirements

- OS: Windows 10 or Windows 11 (64-bit).
- .NET 8 Desktop Runtime (for the lightweight version).

## Installation

1. Go to the **Releases** section of this repository.
2. Download the latest `EndlessDesktop_v1.0.0.zip` archive.
3. Extract the archive to any folder on your computer.
4. Run `EndlessDesktop.exe`.

*Note: If you downloaded the lightweight version, you must have the [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/8.0) installed.*

## Usage & Controls

- `Ctrl + Mouse Wheel`: Zoom in / Zoom out.
- `Middle Mouse Button`: Pan the canvas.
- `Left Mouse Click`: Select a window (highlights it with a blue border).
- `Space`: Smoothly fly the camera to the selected window (Zoom to fit).
- `Enter`: Fly to the selected window and bring it to the foreground.
- `Left Mouse Drag`: Move a window across the canvas.
- `Right Mouse Click`: Open the settings menu (themes, wallpapers, etc.).
- `Ctrl + S`: Save the current layout manually.
- `Esc`: Minimize the application to the system tray.

## Building from Source

To build the project yourself, you will need the .NET 8 SDK installed.

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/EndlessDesktop.git

    Navigate to the project folder:
    bash

    cd EndlessDesktop

    Build and run:
    bash

    dotnet run

License

This project is licensed under the MIT License. See the LICENSE file for details.
Support

If you find this project useful and would like to support its development, you can do so via the links below:

    [DonationAlerts / Boosty Link Here]
