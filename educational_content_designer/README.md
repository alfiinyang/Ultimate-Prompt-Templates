# Educational Content Designer Prompt Templates

This repository contains prompt templates designed to customize an Educational Content Designer LLM for creating YouTube-style visual learning slides for children.

<img src="./sample_slides/boy_n_robot_xray.gif" width="30%">

![Boy & Robot X-Ray](./sample_slides/boy_n_robot_xray.gif)  ![Welcome Slide](./sample_slides/intro_animation.gif)

## File Overview

  * **`system_prompt.txt`**: Defines the specific workflow and design system the model will follow to create sticker-based micro-slides.
  * **`user_prompt_template.txt`**: Provides the essential context and parameters (topic, goal, audience) the model needs to apply the workflow correctly.
  * **`user_prompt_template-mini.txt`**: A smaller version of the context and parameters. Suitable for quick and simple output, especially as a continuation of a conversation where `user_prompt_template` has already been perfectly executed.

## Setup Instructions

1.  **Upload Knowledge Base**: Download `system_prompt.txt` and upload it to the knowledge/files section of your custom model:
      * **Google Gemini**: "Knowledge"
      * **ChatGPT**: "Project Sources"
      * **Claude AI**: "Project Files"
    It can alternatively be used as the system prompt.
2.  **Configure Instructions**: Replace the placeholders in `user_prompt_template.txt` or `user_prompt_template-mini.txt` with the relavant information for your project, then copy and paste it in the chat with your customized model.

## Customization

You are encouraged to edit both `system_prompt.txt` and `user_prompt_template.txt` to better suit your specific educational use case, target age range, or unique character requirements.