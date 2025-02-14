# Video-Summarizer-GenAI

## Overview

This repository contains a web-based video summarizer application that allows users to upload video files and receive summaries generated by a machine learning model. The frontend is built using HTML and CSS, with JavaScript handling the upload and progress tracking. The backend is implemented in Python using CGI for handling file uploads and interacting with the Google Generative AI API.

## Features

- **File Upload:** Users can upload MP4 video files.
- **Progress Indicator:** A progress bar shows the upload status.
- **Gradient Background:** A dynamic gradient background enhances the visual appeal.
- **Summary Generation:** The backend processes the video and returns a summary.

## Prerequisites

Before running the application, ensure you have the following:

- **Python 3.x**: Required for the CGI script.
- **Google Generative AI API Key**: Obtain an API key from the Google Cloud Console.
- **Web Server**: A server with CGI support, such as Apache or Nginx.

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/kgelli/Video-Summarizer-GenAI.git
cd Video-Summarizer-GenAI
