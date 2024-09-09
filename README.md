# Multi_Agents_CrewAI

Multi-Agent System for Topic Research, Blog Writing, and LinkedIn Posts
#Overview
This Python script sets up a multi-agent system using the crewai library. The system consists of three agents: the Topic Research Agent, the LinkedIn Post Creator, and the Blog Writer. Each agent has specific roles and responsibilities:

1.Topic Research Agent:
  Goal: Search for relevant information on a given topic from a specified YouTube video.
  Expertise: Specializes in AI, Data Science, Machine Learning, and Generative AI.
  Tools: Utilizes the YouTube video search tool.
2.LinkedIn Post Creator:
  Goal: Write a concise LinkedIn post summary based on the transcription provided by the Topic Research Agent.
  Expertise: Crafting engaging LinkedIn posts with trending hashtags for maximum visibility.
3.Blog Writer:
  Goal: Create a comprehensive blog post from the transcription provided by the Topic Research Agent.
  Expertise: Developing in-depth, well-structured blog content that explains technical concepts clearly.
  
# Installation
  Install the necessary Python libraries: pip install crewai crewai_tools youtube-transcript-api yt-dlp

  Set up your OpenAI API key and specify the GPT model-ID in the environment variables.
 # Usage
  Run the Python script: python multi_agents.py

#The script will execute the agents’ tasks and generate output files:
  blog-post.md: The markdown-formatted blog post.
  linkedin-post.md: The LinkedIn post.

# Output Files
  Blog Post: The blog post provides detailed information on the topic, including an introduction, step-by-step guides, and a conclusion.
  LinkedIn Post: The LinkedIn post summarizes the key points from the video transcription.
