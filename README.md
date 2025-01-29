# LLMSeeds

LLM Seeds are PDFs that are interactions with LLMs that can be passed between people for advanced communication methods. 

This code is a method for Creating Transcripts from Podcasts in an RSS feed. 
In this case, having transcripts from multiple podcasts that can be integrated into a LLM for comparison and analysis is the basic idea. 

Basic Code to Download Audio from RSS Feed (Podcast) and Transcribe for LLM Usage

* Need to create your key env file with OpenAI API

Suggest using https://castos.com/tools/find-podcast-rss-feed/

* Could be expanded to allow you to download particular episodes

Prompts you to enter the URL

Prompts number of episodes to download

Estimates the cost, displays and prompts whether to proceed

Downloads audio, segments for OpenAI Whisper application, creates transcript segments, agglomerates into one transcript file, deletes the audio segments after each downloaded episode (save memory)
