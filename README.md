YTSearch - Local Setup Guide
Overview

YTSearch is a web application that allows users to search through YouTube captions of videos from a specific YouTube channel. It utilizes YouTube's caption system to download and catalog captions, enabling users to query them for specific phrases.

Prerequisites

Before setting up YTSearch, ensure you have the following installed:

Node.js (version 16 or higher)

npm (Node Package Manager)

You can download Node.js from https://nodejs.org/
.

Installation Steps

Clone the Repository

Open your terminal or command prompt and run:

git clone https://github.com/MRJAXMAX/YTSearch.git
cd YTSearch


Install Dependencies

Run the following command to install the necessary dependencies:

npm install


Configure Environment Variables

Locate the .env file in the root directory of the project and edit the following line:

VITE_YT_API_KEY=your_youtube_api_key


Replace your_youtube_api_key with your actual YouTube API key. If you don't have one, you can obtain it from the Google Developers Console
.

Run the Development Server by opening a terminal or cmd and enter the command:

npm run dev


The application should now be running locally. Open your browser and navigate to http://localhost:5173 to access the YTSearch interface.

Usage

Once the application is running:

Enter a YouTube channel, video or whatever into the search bar.

The app will display a list of videos from that channel.

Click on a video to view its captions.

Use the search functionality to find specific phrases within the captions.

Notes

Ensure your YouTube API key is correct and has the necessary permissions to access YouTube Data API v3.

The application is designed for local development and may require additional configuration for production deployment. WORK IN PROGRESS
