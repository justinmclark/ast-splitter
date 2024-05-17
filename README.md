# AST Text Spitter

For LLMs to write quality code, context is everything. I believe that abstract syntax trees "ASTs" in combination with filesystem information (e.g. directory structure, location of tests, etc.) is crucial for getting the most useful context.

This project aims to create a code text splitter that is language-agnostic and can work well in real-time LLM+coding environments (think GitHub copilot, Cursor, etc.).
