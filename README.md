# Hardware Monitor using Go and HTMX

This is a modern hardware monitoring web application built with Go and HTMX. The application leverages WebSockets to dynamically fetch and display real-time system data, such as CPU usage, memory usage, and disk space.

## Features
- Real-time system monitoring
- WebSocket integration for live updates
- Clean, responsive UI using HTMX
- Cross-platform support (Windows, macOS, Linux)

## Requirements
- Go 1.20+
- HTMX (included via CDN)
- Web Browser (Chrome, Firefox, Edge, etc.)

## Installation
```bash
git clone https://github.com/username/hardware-monitor-go
cd hardware-monitor-go
go mod tidy
go run main.go
```

Visit `http://localhost:8080` in your browser.

## Usage
1. Start the application by running `go run main.go`
2. Open a web browser and navigate to `http://localhost:8080`
3. The system's hardware information will automatically refresh in real-time.

## ScreenShots 

![image](https://github.com/user-attachments/assets/13287bc9-329e-4bc2-8a71-ab139a0eedff)
