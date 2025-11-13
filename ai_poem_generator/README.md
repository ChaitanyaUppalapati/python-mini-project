\# GenAI Poem Generator (CLI)



A tiny CLI that generates a short poem about any theme using a small language model (`distilgpt2` via Transformers).



\## Features

\- Prompted for \*\*theme\*\*, optional \*\*form\*\* (free/haiku/sonnet/etc.), and desired \*\*line count\*\*

\- Deterministic decoding (no sampling) for stable outputs

\- Lightweight tests with a \*\*fake pipeline\*\* so CI doesn't download models



\## Install

```bash

pip install -r requirements.txt



