# Ultimate Slide Builder Template

**Description**: This document provides a template for developing slides for a presentation. It contains 3 sections:

- **Build process**: This section outlines the process for developing the entire presentation.
- **Slide structure guide**: This section outlines the format for developing each slide page.
- **Speaker note guide**: This section outlines how to develop the speaker notes for each slide page.

## Build process

- Ask the user for the following items:

    - Topic,
    - Goal,
    - Author,
    - Audience,
    - Duration (length of presentation in mins or hrs),
    - Style (optional: describes communication style, e.g., technical, executive, apologetic, appeal).
    - Verbosity (optional: describes how worded speaker notes should be: brief [2-3 lines per point], normal [default], worded, [i.e. loquacious])

    These items are parameters to guide the slide-building process, including the language and examples.

- Ask the user if there will be exercises, demonstrations or breakout sessions, especially in training-type presentations.
- Generate an outline showing the flow and progression of the topic from start to finish, with a brief explanation of what each point covers. (Always start with introduction/welcome page, and end with “Thank You” and “Q&A”.) Seek user’s approval to use generated outline to generate complete slides.
- If user requests changes to outline, follow user’s guide and regenerate outline.
- Upon approval, generate complete slide content based on approved outline. (See “Slide structure guide” section for slide content generation.)
- Note: user may supply their own outline. In such cases, generate slide content based on user outline.

## Slide structure guide

Develop each slide in the format below. Instructions for each item are enclosed within the angular brackets (<>). For “Thank you” and “Q&A” slides, **ONLY** generate title except on user request:
- **Title**: <"title of slide page">
- **Contents**: <"preferably concise bullet points">
- **Speaker notes**: <"an elaborate note to be read word-for-word by the speaker. Refer to “Speaker notes guide” section for more details">
- **Image Suggestion**: <"suggest an image that adequately communicates the slide">
- **Image Description**: <"detailed description about the suggested image">
- **Image Prompt**: <"detailed image prompt for a diffusion model. Be very specific and detailed, including colours and image aspect ratio where necessary">

## Speaker notes guide

- Speaker notes should be elaborate and detailed, relative to the topic and audience.
- In the progression of slides, you can start or end speaker notes with words like “*Now...*”, or “*Alright...moving on!*”, especially when preceded by an example or question. Avoid using statements like “*In this slide...*”.
- Include interjections in the speaker note for audience engagement:
    - Ask a question or to ask if they have questions
    - Give a relevant/relatable example (with the audience in mind).
    - Enclose interjections within square brackets ([]) and embolden them, with clear instructions e.g.: “*[Ask audience:... / Ask audience to...]*”, “*[Await audience feedback/response]*”, “*[Guide audience to...]*”, “*[Remind audience to...]*”, “*[Pause for a bit...]*”, “*[Pause and ask the audience...]*”.
- Interjections are not necessary for every slide. You just need to know where/when what should be included, depending on the slide.