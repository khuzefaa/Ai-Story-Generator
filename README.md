# Ai-Story-Generator
The AI Story Generator is a comprehensive tool that creates engaging short stories using both offline (GPT-2) and online (OpenAI GPT) models. It features multiple story generation modes, customizable prompts, and an interactive interface that makes storytelling accessible to everyone.
✨ Key Features

Multiple AI Models: Choose between GPT-2 (offline) or OpenAI GPT (premium)
Interactive Interface: User-friendly prompts and menu system
Flexible Prompt Generation:

Random story prompts with characters, settings, and conflicts
Genre-based prompts (Fantasy, Sci-Fi, Mystery, Adventure, Horror, Romance)
Custom user-defined prompts


Story Customization: Adjustable story length and creativity temperature
Batch Generation: Create multiple stories at once
File Export: Save generated stories to text files
Story Analytics: Get statistics about your generated content
Story Cleanup: Automatic formatting and sentence structure improvement

🚀 Quick Start
Google Colab (Recommended)

Open Google Colab
Create a new notebook
Copy and paste each cell from the provided code
Run cells in order (1-7)
Start generating stories!

Local Installation
bash# Clone or download the code
pip install openai transformers torch

# Run the Python script
python ai_story_generator.py
📋 Requirements

Python 3.7+
PyTorch
Transformers (Hugging Face)
OpenAI (optional, for premium features)

🎮 How to Use
1. Basic Story Generation
python# Generate a story with random prompt
story = story_gen.generate_story_gpt2("Once upon a time,", max_length=200)
print(story)
2. Interactive Mode
Run the interactive interface to:

Choose between random, genre-based, or custom prompts
Adjust story parameters
Get instant story generation

3. Batch Generation
python# Generate multiple stories at once
stories = generate_multiple_stories(5)  # Creates 5 stories
🎯 Story Generation Modes
Random Prompts
Combines random elements:

Characters: brave knight, young wizard, mysterious stranger, robot, etc.
Settings: haunted castle, distant planet, enchanted forest, cyberpunk future, etc.
Conflicts: solve mystery, save world, break curse, face impossible choice, etc.

Genre-Based Prompts
Pre-crafted starting points for specific genres:

🏰 Fantasy: Magical realms and dragons
🚀 Sci-Fi: Future worlds and space exploration
🔍 Mystery: Secrets and investigations
⚔️ Adventure: Treasure hunts and quests
👻 Horror: Dark atmospheres and supernatural elements
💕 Romance: Love stories and relationships

Custom Prompts
Start with your own creative prompt and let AI continue the story.
⚙️ Configuration Options
Story Parameters

max_length: Control story length (50-500 tokens)
temperature: Creativity level (0.1-1.0)

Low (0.1-0.3): More focused and coherent
Medium (0.4-0.7): Balanced creativity
High (0.8-1.0): Very creative and unpredictable



Model Selection

GPT-2: Free, offline, good quality
OpenAI GPT: Premium, requires API key, excellent quality
