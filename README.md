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




## Configuration

LocalGhost processes strict Content Security Policy (CSP) headers for security. If you are developing and adding new external resources (images, scripts), ensure `electron/main.cjs` is updated to allow them.

## License

Copyright © Sukhesh. All rights reserved.
