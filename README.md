# Context-Resetter
A simple but effective tool to cure LLM context degredation, recency bias, and conversational overfitting. Can also be used for non-LLM purposes such as Zoom transcripts, messy notes, etc.

The Problem: In long-winded chats, context windows get bloated. The AI's suffer from recency bias, and the conversation diverges overfitting to the unintentional subconscious direction. Finding the original signal in the noise becomes laborious.

The Fix: This tool acts as a "clean up" brick. It forces top AI engines to compress rambling chat histories in a targeted manner. It extracts the core goal, current state, and constraints so you can start a fresh, hallucination-free session.

Minor Notes:

BYO key to swap between Anthropic, Gemini, OpenAI, Deepseek, Groq, and OpenRouter models based on your token budget. Recommended to use an LLM seperate from the current conversation to provide the best results.

100% static execution. API keys and document parsing (drag-and-drop .pdf and .docx) run entirely locally in the browser with zero backend.

Bypasses standard "lossy compression" by forcing models to categorize unstructured dumps into a rigid, non-conversational format.
