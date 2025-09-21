# Generate_Blog
Built a Chatbot which generates Blog with word count.

📝 Blog Generator

A simple AI-powered blog generator built with Transformers and Gradio.
It creates well-structured blog posts with exact word counts and strong endings based on the user’s topic, audience, and desired word count.

✨ Features

Generate blog posts with a custom title, audience, and word count
Automatically ensures exact word count
Adds a strong conclusion to every blog post
Title displayed separately for a clean look
Built using TinyLlama (can be swapped for bigger models for better results)

📝 How It Works

You enter the blog title, target word count, and audience.
The app sends a prompt to the TinyLlama model using the Hugging Face Transformers pipeline.
The model generates content; the code trims or pads it to ensure exact word count and a strong conclusion.
You get a polished blog post instantly.

🧩 Project Structure
.
├── app.py               # Main application code
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation

⚡ Customization

Change model_name in app.py to use a larger instruction-tuned model for better quality.
Adjust max_new_tokens if you want longer blogs.
Modify the fallback_conclusion in app.py to set your own default ending.

✅ Quick Preview
When you run it, the UI looks like this:

📝 Blog Generator
[Blog Title] [Word Count] [Audience]
[Generate Blog Button]
[Generated Blog Output]
