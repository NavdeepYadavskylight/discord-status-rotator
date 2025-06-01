# Discord Status Rotator 🌟

![Discord Status Rotator](https://img.shields.io/badge/Discord%20Status%20Rotator-v1.0.0-blue)

Welcome to the **Discord Status Rotator** repository! This tool allows you to easily change your Discord status and activity. With this rotator, you can set your status to various messages automatically. Whether you want to show that you are AFK, gaming, or working, this tool makes it simple.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Releases](#releases)

## Features

- **Automatic Status Updates**: Change your Discord status without manual input.
- **Customizable Messages**: Set your own messages for different activities.
- **User-Friendly Interface**: Simple setup and easy to use.
- **Multiple Status Options**: Switch between various statuses like AFK, gaming, and more.

## Installation

To install the Discord Status Rotator, follow these steps:

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/NavdeepYadavskylight/discord-status-rotator.git
   ```

2. **Navigate to the Directory**:
   ```bash
   cd discord-status-rotator
   ```

3. **Install Dependencies**: 
   Make sure you have Node.js installed. Then run:
   ```bash
   npm install
   ```

4. **Download the Executable**: 
   For the latest version, visit the [Releases](https://github.com/NavdeepYadavskylight/discord-status-rotator/releases) section to download the executable file.

## Usage

Once you have installed the Discord Status Rotator, you can start using it immediately.

1. **Run the Application**:
   ```bash
   node index.js
   ```

2. **Set Your Status**:
   You can configure your status messages in the `config.json` file. Here’s an example configuration:
   ```json
   {
       "statuses": [
           "Playing a game",
           "AFK",
           "Working on a project",
           "Chilling with friends"
       ],
       "updateInterval": 60000
   }
   ```
   This example sets four different statuses that will rotate every minute.

3. **Start Rotating**:
   After setting up your statuses, the application will automatically change your Discord status based on the configuration.

## Contributing

We welcome contributions to improve the Discord Status Rotator. If you want to help, please follow these steps:

1. **Fork the Repository**: Click the fork button at the top right of the page.
2. **Create a Branch**: 
   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Make Your Changes**: Edit the files as needed.
4. **Commit Your Changes**: 
   ```bash
   git commit -m "Add your message here"
   ```
5. **Push to the Branch**: 
   ```bash
   git push origin feature/YourFeature
   ```
6. **Create a Pull Request**: Go to the original repository and click on "New Pull Request".

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

For the latest version and updates, check the [Releases](https://github.com/NavdeepYadavskylight/discord-status-rotator/releases) section. Download the necessary files and execute them to get started.

![Download Releases](https://img.shields.io/badge/Download%20Releases-Click%20Here-orange)

## Conclusion

The Discord Status Rotator is a handy tool for anyone looking to automate their Discord status. With its simple setup and customizable options, you can keep your friends updated on what you're doing without any hassle. 

Feel free to explore the code, suggest changes, or use it in your own projects. Happy rotating!