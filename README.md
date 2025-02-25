# Script to Video Automation

## Overview
This project automates the process of transforming a transcript into a structured video presentation. The pipeline includes **cleaning transcripts**, **clustering text into slides**, **generating summarized bullet points**, **converting text to speech**, **integrating speech into PowerPoint slides**, and **finalizing a video output**. The goal is to streamline the creation of educational or presentation-based videos while minimizing manual effort.

## Key Features
- **Transcript Cleaning**: Prepares raw text for processing.
- **Slide Text Grouping**:
  - Uses **soft clustering** to organize topics per slide.
  - Considering a shift to **hard-rule clustering** to reduce API usage costs.
- **Text Summarization**: Generates concise bullet points for each slide.
- **Text-to-Speech Conversion**:
  - Uses **Speechify** for audio generation, with tuning options for pitch, rate, and emotion.
  - **Elai.io** is an alternative tool.
- **Speech-to-PowerPoint Integration**:
  - Merges AI-generated bullet points with audio into slides.
  - Can be done using **Elai.io** or local Python automation.
- **Video Editing**:
  - Uses **Wondershare Filmora** for bulk edits if needed.
  - Python-based tools can be explored for automation.

## Tools and Technologies
- **Python**: Core automation logic for text processing and slide generation.
- **Speechify API**: Converts text to speech.
- **Elai.io**: Potential tool for AI-driven video generation.
- **PowerPoint Automation**: Python-based integration of slides and audio.

## Workflow
1. **Input**: Raw transcript.
2. **Processing**:
   - Text cleaning for LLM input.
   - Clustering text into slide-based topics.
   - Summarizing into key bullet points.
3. **Audio Generation**:
   - Converts summarized text into voice narration.
4. **Slide Creation**:
   - Integrates AI-generated bullet points into PowerPoint.
   - Aligns slides with corresponding audio.
5. **Final Video Output**:
   - Edits and exports video using Filmora or Python-based tools.

![Screenshot 2025-02-24 at 7 10 39 PM](https://github.com/user-attachments/assets/3081f57b-3b96-40cf-ad42-98f5ece8d63a)
