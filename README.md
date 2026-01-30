# LocalGhost

**Premium Network Scanner and Forensics Tool for Windows**

LocalGhost is a comprehensive desktop application designed for network analysis, security monitoring, and device forensics. Built with modern web technologies and wrapped in Electron, it offers a visually stunning and responsive interface for managing your local network environment.

## Features

*   **Network Scanner**: rapidly discover all devices connected to your local network with vendor identification.
*   **Jitter Monitor**: Real-time monitoring of network stability and latency to detect anomalies.
*   **Security Scout**: Assessment tool to identify potential security vulnerabilities on your network devices.
*   **Timeline Forensics**: Visual timeline of device activity to track connections and disconnections over time.
*   **WOL Scheduler**: Schedule and perform Wake-on-LAN operations to remotely power on devices.
*   **Startup Guardian**: Manage and monitor applications that launch at system startup.

## Technologies

*   **Core**: [Electron](https://www.electronjs.org/), [React](https://react.dev/), [Vite](https://vitejs.dev/)
*   **Styling**: [TailwindCSS](https://tailwindcss.com/)
*   **Data Visualization**: [Chart.js](https://www.chartjs.org/), [Vis.js](https://visjs.org/)
*   **Network Utilities**: Custom Node.js implementations for scanning, pinging, and MAC address lookup.

## Installation

To run LocalGhost locally, ensure you have [Node.js](https://nodejs.org/) installed, then follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/sukheshcs/localghost.git
    cd localghost
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Run in development mode:**
    ```bash
    npm run dev
    ```
    This command runs both the React (Vite) server and the Electron main process concurrently.

## Building for Production

To create a distributable Windows installer and AppX package:

```bash
npm run build
```

This will generate the output in the `release` directory, including:
*   NSIS Installer (`.exe`)
*   AppX Package (`.appx`) for Microsoft Store submission.

## Configuration

LocalGhost processes strict Content Security Policy (CSP) headers for security. If you are developing and adding new external resources (images, scripts), ensure `electron/main.cjs` is updated to allow them.

## License

Copyright © LocalGhost Dev. All rights reserved.
