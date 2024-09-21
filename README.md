# Anime-on-CLI

Welcome to **Anime-on-CLI**! 🎉

This repository provides a comprehensive guide on how to watch your favorite anime using the command line interface (CLI).

## 🚀 Getting Started

Follow these steps to get started with watching anime in your terminal:

### Step 1: Install Git

If you don't have Git installed, run the following command in Command Prompt or PowerShell:

```bash
winget install --id Git.Git -e --source winget
```
### Step 2: Install Scoop

Open Git Bash.
Run this command to install Scoop:
```bash
iwr get.scoop.sh -useb | iex
```
If you encounter an error about the execution policy not being set, run this command first:
```
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
```
### Step 3: Install ani-cli
In Git Bash, run the following command:
```bash
scoop install ani-cli
```
### Step 4: Install VLC and fzf
Use Scoop to install VLC and fzf with this command:
```bash 
scoop install fzf vlc
```
### Step 5: Download the Batch File
Clone or download the any of the batch file from the repository and try to run it.
one piece.bat , berserk.bat ,generic.bat

### 📚 Prerequisites

- Ensure you have the following installed:
  - Git
  - Scoop
  - fzf
  - VLC
  - [ani-cli](https://github.com/pystardust/ani-cli) (Anime on CLI)

## 📖 Usage

You can open your Git Bash, then run `ani-cli --vlc` to search for your anime. Alternatively, you can simply run one of the batch files to directly see the episode list.

### Option 1: Using the Command Line

1. Open your terminal or Git Bash.
2. Run the command to search for your favorite anime:

   ```bash
   ani-cli search 'Your Favorite Anime'
   
### Option 2: Using Batch Files

Run any of the following batch files to directly see the episode list:
- `one piece.bat`
- `berserk.bat`
- `Generic.bat`

## 📌 Creating a Shortcut with `Generic.bat`

You can use the `generic.bat` file to create a shortcut for quickly accessing your favorite anime. Here’s how to do it:

### Step 1: Edit `Generic.bat` in text editor
### Step 2: Replace 'some-anime-name' with name of anime you want to watch 
for example:
```
"C:\Program Files\Git\bin\bash.exe" --login -i -c "ani-cli 'some-anime-name' --vlc"
```
to
```
"C:\Program Files\Git\bin\bash.exe" --login -i -c "ani-cli 'one piece' --vlc"
```
### Step 3: Save the file ,change the name if you want it.
### YOU WILL HAVE A SHORTCUT BAT FILE TO YOUR ANIME <3.




