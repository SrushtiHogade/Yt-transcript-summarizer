# Yt-transcript-summarizer
This project allows users to extract transcripts from YouTube videos and generate concise summaries for quick understanding. It's built using Python and Flask, and leverages the `youtube_transcript_api` for retrieving captions.

# Features include:

-Accepts any public YouTube video URL

-Extracts transcripts using youtube_transcript_api

-Summarizes text using LexRank algorithm (Sumy library)

-Multiple summary sizes: Small (10 lines), Medium (20), Large (30)

-Download summary as .txt file

-Displays thumbnail of the video

-Includes sections like Login, FAQs, Reviews, Contact Us

# Functional Flow
1)User submits a YouTube link
2)Video ID is extracted and passed to the API
3)Transcript text is fetched
4)LexRank summarizes the transcript based on user-selected length
5)Summary is rendered along with word count and video thumbnail
6)Summary can be downloaded

  
