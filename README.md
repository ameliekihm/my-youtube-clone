# YouTube Clone Project 📌
<img width="1229" height="670" alt="Image" src="https://github.com/user-attachments/assets/a4a736d2-b8d1-4338-a5ac-c21d6ef86d2f" />
<img width="1156" height="671" alt="Image" src="https://github.com/user-attachments/assets/a4fe0993-e09b-4699-8418-4ea54354d423" />
<img width="1160" height="665" alt="Image" src="https://github.com/user-attachments/assets/ffb64fed-4360-49e8-9f89-c639962444bf" />

Click here to view the live project deployed on Netlify. ➡️ https://amelie-youtube.netlify.app/

## Description

Welcome to the YouTube Clone Project using the YouTube API! This application, built with React, allows you to efficiently search for YouTube videos, view video details, and explore related videos. 

## Features

- **Search Videos**: Quickly search for YouTube videos by keywords.
- **View Video Details**: Watch videos and see detailed information about them.
- **Related Videos**: Explore videos related to the current video from the same channel.
- **Responsive Design**: The website is responsive, and the number of videos displayed changes when the window size is adjusted.

## Technologies Used

- **React**: For building the user interface.
- **Tailwind CSS**: For styling the application.
- **React Router**: For handling navigation and routing.
- **React Query**: For data fetching and state management.
- **YouTube API**: For retrieving video data from YouTube.

## Components

### 1. SearchHeader

The `SearchHeader` component allows users to search for videos. It includes an input field for entering the search query and a button to submit the search.

### 2. VideoCard

The `VideoCard` component represents an individual video in the search results or related videos list. It displays the video thumbnail, title, channel name, and upload date. Clicking on the video navigates to the video details page.

### 3. VideoDetail

The `VideoDetail` component displays detailed information about a selected video. It includes an embedded video player, video title, channel information, and video description. It also shows related videos from the same channel on the right side of the video.

### 4. ChannelInfo

The `ChannelInfo` component displays information about the channel that uploaded the video, including the channel's name and profile image.

### 5. ChannelPlaylist

The `ChannelPlaylist` component shows a list of related videos from the same channel.

## Context

### YoutubeApiContext

The `YoutubeApiContext` provides access to the YouTube API client. This context is used by various components to fetch video data.

## Styling

The application uses `Tailwind CSS` for styling. Tailwind CSS allows for easy and efficient styling by applying utility classes directly in the JSX code. The application supports a responsive design, adjusting the number of videos displayed based on the window size.

