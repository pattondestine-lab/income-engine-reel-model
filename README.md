# The Reel Treatment speech model

This repo hosts the speech-to-text model used by **The Reel Treatment** skill in The Income Engine. The skill downloads it automatically the first time it runs in a chat. Members don't need to do anything here.

- File: `ggml-base.en-q5_1.bin`, whisper.cpp's English "base" model, 5-bit quantized
- SHA-256: `4baf70dd0d7c4247ba2b81fafd9c01005ac77c2f9ef064e00dcf195d0e2fdd2f`
- Source: [whisper.cpp](https://github.com/ggml-org/whisper.cpp) by ggml-org, built from OpenAI's Whisper. Both are released under the MIT License, and their notice is kept below.

---

MIT License. Copyright (c) 2023-2024 The ggml authors. Copyright (c) 2022 OpenAI.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
