# Mini-gpt-from-scratch
Minimal GPT-style Transformer in PyTorch (decoder-only), from scratch. 
- Character-level tokenizer (works on any text string you paste)
- Causal self-attention with multi-heads
- Transformer blocks with pre-LayerNorm + residuals
- Tied token embeddings
- Simple training loop (AdamW, grad clip) - Text generation with temperature &amp; top-k
