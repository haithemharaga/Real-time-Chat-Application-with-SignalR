<div align="center">

# 💬 Real-time Chat Application with SignalR

**Instant, bidirectional messaging built on ASP.NET Core SignalR — messages appear live, no refresh.**

![.NET](https://img.shields.io/badge/.NET-8-512BD4?logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-backend-239120?logo=csharp&logoColor=white)
![SignalR](https://img.shields.io/badge/SignalR-realtime-512BD4?logo=dotnet&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-live-010101?logo=socketdotio&logoColor=white)

</div>

---

## Overview

A real-time chat application powered by **ASP.NET Core SignalR**. SignalR manages a persistent connection (WebSockets where available, with automatic fallbacks) so messages are pushed to every connected client the instant they're sent.

## ✨ Features

- ⚡ **Live messaging** — messages broadcast to all clients in real time.
- 🔌 **SignalR Hub** managing connections and message dispatch.
- 🌐 **WebSocket transport** with graceful fallback.
- 🧱 **ASP.NET Core** backend, ready to extend with rooms, usernames, and history.

## 🛠️ Tech Stack

| Area | Tech |
|------|------|
| Language | C# |
| Framework | ASP.NET Core |
| Real-time | SignalR |

## 🚀 Getting Started

**Prerequisites:** [.NET SDK](https://dotnet.microsoft.com/download)

```bash
git clone https://github.com/haithemharaga/Real-time-Chat-Application-with-SignalR.git
cd Real-time-Chat-Application-with-SignalR
dotnet restore
dotnet run
```

Open the app URL shown in the console, then open a second tab to watch messages sync live between them.

## 📁 Project Structure

```
RealtimeChat/
├── Program.cs         # app + SignalR hub wiring
├── appsettings.json   # configuration
└── RealtimeChat.sln
```

---

<div align="center">
Built by <a href="https://github.com/haithemharaga">Haithem Haraga</a>
</div>
