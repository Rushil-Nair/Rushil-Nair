# Hi, I'm Rushil

MS CS student at USC, graduating December 2026. I work on making LLMs run fast and well:
on-device inference, LLM serving, and retrieval. Looking for new-grad ML / inference
engineering roles starting January 2027.

### Projects

**[SpecEdge](https://github.com/Rushil-Nair/SpecEdge)**: on-device tool-calling agent
- LoRA fine-tune of Llama 3.2 3B: 48.6% → 65.7% on 591 held-out tool-calling tasks
- W4A16 with Qualcomm AIMET, running fully on the Snapdragon 8 Elite NPU within 2.5 points of full precision
- C++ agent runtime on llama.cpp, plus a llama.cpp server fix that raised throughput 2.6x at 8 users

**[Insight RAG](https://github.com/Rushil-Nair/Insight-RAG-Recommendation-System)**: review-grounded product search
- Hybrid BGE-M3 retrieval + cross-encoder re-ranking over 15.5k products: nDCG@10 0.79 vs 0.68 for BM25
- Distilled a 9B LLM's rankings into a 568M re-ranker: nDCG@10 0.753 → 0.808

### Contact
rushilan@usc.edu · [LinkedIn](https://linkedin.com/in/rushil-nair-38a15b234)
