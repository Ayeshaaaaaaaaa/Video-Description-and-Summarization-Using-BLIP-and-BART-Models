# Video-Description-and-Summarization-Using-BLIP-and-BART-Models
This project processes videos by extracting frames, generating detailed visual descriptions for each frame using the BLIP model, and then summarizing these descriptions with the BART model.<br>
## Key features include:

Frame Extraction: Extracts 1 frame per second from the input video for efficient processing.<br>
Visual Captioning: Uses Salesforce's BLIP image-captioning model to generate natural language descriptions for each extracted frame.<br>
Summarization: Combines the generated frame descriptions and summarizes them into a cohesive video summary using Facebook's BART large CNN model.<br>
