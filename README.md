## Overview
This project implements an image captioning and search engine using OpenAI's CLIP model and BLIP model. It fulfills both assignments with a complete solution.

## Assignment 1: Write-up on Hugging Face
The notebook contains detailed explanations of:
- Hugging Face Agents
- Hugging Face Pipeline for text generation
- HF Inference Endpoints
- Image generation models feedback and exploration

## Assignment 2: CLIP Model Implementation
- **Part 1**: Generate captions for 15 different images using CLIP and BLIP models
- **Part 2**: Build an image search engine with text and image-based search capabilities

## Features
- **Dual Captioning**: Uses both CLIP (with candidate captions) and BLIP (generative) approaches
- **Text Search**: Find images using natural language descriptions
- **Image Search**: Upload an image to find visually similar ones
- **Model Comparison**: Evaluates different CLIP variants and approaches

## Installation

1. **Clone or download the files**
2. **Install dependencies**:
   ```cmd
   pip install -r requirements.txt
   ```

## Usage

### Running the Jupyter Notebook
Open and run `HuggingFace_Day4 (2).ipynb` to see the complete analysis and development process.

## Technical Details

### Models Used
- **CLIP (ViT-B/32)**: For image-text similarity and feature extraction
- **BLIP**: For automatic image captioning
- **Multiple CLIP variants**: Comparison of different architectures

### Architecture
- **Feature Extraction**: 512-dimensional CLIP embeddings
- **Similarity Search**: Cosine similarity for ranking
- **Dual Processing**: Both text-to-image and image-to-image search
- **Caching**: Efficient model and data caching

### Dataset
- 15 sample images from Unsplash (free to use)
- Diverse categories: landscapes, animals, cities, objects, etc.
- Automatic caption generation for each image


## Results
- **Caption Quality**: BLIP provides more natural captions, CLIP offers structured classification
- **Search Accuracy**: High relevance for semantic queries and visual similarity
- **Performance**: Sub-second search on the sample dataset
- **User Experience**: Intuitive interface with real-time feedback
