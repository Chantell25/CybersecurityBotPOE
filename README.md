# CybersecurityBotPOE

# Cybersecurity Awareness Bot

A console-based chatbot that educates users about cybersecurity best practices including password safety, phishing detection, and safe browsing habits.

## Features

- [x] Voice greeting on startup (WAV format)
- [x] ASCII art logo display
- [x] Personalized user interaction with name validation
- [x] Cybersecurity Q&A response system
- [x] Input validation for empty or unrecognized queries
- [x] Colored console UI with typewriter effect and borders
- [x] Multi-file code structure (Program.cs, Chatbot.cs, UIManager.cs, ResponseSystem.cs, AudioPlayer.cs)
- [x] GitHub Actions CI/CD workflow
- [x] Minimum 6 meaningful commits

## Requirements

- .NET 8.0 SDK
- Windows OS (for full audio support)
- System.Media.dll (for WAV playback)

## Setup Instructions

1. Clone the repository
2. Add `greeting.wav` file to project root
3. Run `dotnet restore`
4. Run `dotnet build`
5. Run `dotnet run`

## Usage

Run the application and interact with the chatbot. Type 'help' for available commands or 'exit' to quit.

## CI Status

![Build Status](https://github.com/yourusername/CybersecurityBot/actions/workflows/ci.yml/badge.svg)

## Project Structure
