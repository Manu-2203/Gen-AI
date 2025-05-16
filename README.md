# Cross-lingual Speech and Image Generation


This project focuses on generating educational images from spoken input to support visual learning in middle-school science and social studies. It starts by transcribing spoken prompts using OpenAI's Whisper model, converting speech into accurate text. 

The transcribed text is then passed to Janus, a powerful text-to-image generation model, which produces images based on the prompt’s content. To ensure that the generated image aligns well with the original spoken intent, a CLIP-based similarity check is used to validate and rank the output. 

This system helps transform voice-based educational prompts into meaningful visuals, making learning more engaging and interactive.
