# MiniDesk — Remote Desktop & File Sync

An AnyDesk-style remote desktop and file synchronization application 
built from scratch in C#.

## What it does
- Enables remote screen access between a client and server application
- Syncs files between connected machines
- Split into client, server, and shared library projects for clean 
  separation of concerns

## Tech stack
C# · Windows Forms

## Architecture
- `MiniDeskClient` — client-side application
- `MiniDeskServer` — server-side application handling connections
- `MiniDeskShared` — shared models/utilities used by both

## Note
This repo showcases the project's structure. Full source is public — 
see the [live repo](https://github.com/Ummesalma53/MiniDesk).
