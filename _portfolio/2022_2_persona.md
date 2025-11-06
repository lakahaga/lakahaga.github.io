---
title: "Persona-specific Chatbot Model"
excerpt: "Jun - Jul 2023, SmilegateAI<br/>- Developed a style transfer model for the dialogue tailored to the communication style of women in their 20s.<br/>- Multi-turn dialogue data augmentation <br/> - Deployed real-time chat-bot service"
collection: portfolio
share: false
---
### Persona-based Style Transfer for Dialogue
- Developed a persona-consistent style transfer model that adjusts both content and linguistic style to match the communication patterns of women in their 20s.
- Implemented a content classifier to detect whether conversation topics align with the target persona domain.
- Built a style transfer model using:
  - Speech-to-text data extracted from lifestyle and vlog videos of female college students in their 20s
  - Manual and model-assisted cleaning and segmentation into multi-turn conversational form
  - Style adaptation of existing dialogue datasets using persona-conditioned language modeling
- Developed and deployed a real-time multi-turn dialogue demo.

### My Contribution
- Trained and fine-tuned the persona-conditioned style transfer model
- Collected and refined training data via speech recognition → error correction → dialogue-format conversion
- Implemented the real-time multi-turn chatbot demo using Gradio
