# 🧊 lux - Fast key-value storage for Windows

[![Download lux](https://img.shields.io/badge/Download-LuWei911011%2Flux-blue?style=for-the-badge&logo=github)](https://github.com/LuWei911011/lux)

## 🚀 What is lux?

lux is a Redis-compatible key-value store built for speed and simple setup. It stores data in memory and on disk, and it supports vector data for search and embedding use cases.

Use it when you want:

- Fast reads and writes
- Redis-style commands and tools
- Native vector support
- A local database for apps and tests
- A simple way to store app data on Windows

## 💻 System requirements

Before you install lux, check that your PC meets these basic needs:

- Windows 10 or Windows 11
- 64-bit system
- At least 4 GB of RAM
- 500 MB of free disk space
- Internet access to download the files

If you plan to store larger datasets or use vector search, more RAM and disk space can help.

## 📥 Download lux

Visit this page to download:

https://github.com/LuWei911011/lux

On the GitHub page, look for the latest release or the main download files. If you see several files, choose the Windows file that matches your system.

## 🛠️ Install on Windows

Follow these steps to get lux running on Windows.

1. Open the download link above.
2. Find the latest release or the main app file.
3. Download the Windows version to your computer.
4. If the file is a `.zip` file, right-click it and choose Extract All.
5. Open the extracted folder.
6. Find the program file, such as `lux.exe`.
7. Double-click the file to start the app.

If Windows asks for permission, choose Run or Yes.

## ▶️ Start using lux

After you open lux, it should start in a local window or in the background.

Use it like this:

- Keep it open while your app needs data storage
- Connect your app to the local address shown in the app
- Save key-value data for settings, cache, or session info
- Use vector support for embeddings and semantic search

If lux opens a console window, leave it open while you use the database.

## 🔗 Connect from your app

lux works like a Redis-style store, so many apps can connect with a similar setup.

Common connection details may include:

- Host: `127.0.0.1`
- Port: `6379`
- Password: if you set one during setup
- Database number: if your app uses one

If your app already works with Redis, it may work with lux with few or no changes.

## 🧭 Basic things you can do

Here are a few common uses:

- Store app settings
- Keep temporary data in cache
- Save login sessions
- Track counters and rates
- Store embeddings for search
- Build simple local data tools
- Test apps before moving to a full server

## 🧪 Example use cases

lux fits well in these cases:

- A desktop app that needs fast local storage
- A small website that keeps session data
- An AI tool that stores embeddings
- A test environment for Redis-style commands
- A local service that needs quick data lookups

## ⚙️ If the app does not start

Try these checks:

- Make sure you downloaded the Windows file
- Unzip the file if needed
- Run the app as an administrator
- Check that another app is not using the same port
- Restart your PC and try again
- Download the file again if it looks incomplete

If you still cannot open it, check the GitHub page for the newest release files.

## 📁 Where data is stored

lux may store data in a local folder near the app or in a data directory you choose during setup.

If you want to move your data later:

- Close lux first
- Copy the data folder to a safe place
- Open lux again from the new location if needed

## 🔒 Simple setup tips

For a smooth first run:

- Keep the app in a folder you can find later
- Avoid spaces and special characters in the folder name
- Use a normal Windows user account
- Keep one copy of the app in one place
- Back up your data folder if the data matters

## 📚 More info

Project page:

https://github.com/LuWei911011/lux

Repository topics:

database, dragonflydb, embeddings, lux, postgres, redis, rust, supabase, vector