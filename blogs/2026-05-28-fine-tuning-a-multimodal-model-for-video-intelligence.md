---
title: "Fine-tuning a multimodal model for video intelligence"
url: "https://www.mux.com/blog/fine-tuning-a-multi-modal-model-for-video-intelligence"
date: "2026-05-28"
feed_url: "https://www.mux.com/blog/rss.xml"
---
TL;DR I fine-tuned a small multimodal model for Mux-specific video intelligence workflows, like transcript-based summaries and chapter generation. I then integrated that model into the open-source @mux/ai SDK . Along the way, I added Baseten as a provider, generated 10,000 synthetic JSONL training examples, and used LoRA to fine-tune Mistral Small 3.1.
