Mole Code 1.2.2 (PC) / 1.2.4 (Android)
- Reasoning is now detected for real, not guessed from the model name. Mole checks each model once: it asks the server (OpenRouter, Ollama) or sends a short test request and looks at whether the model actually reasons.
- Mole also finds which parameter really controls reasoning on your server (reasoning_effort, reasoning, thinking, enable_thinking), so the selector actually changes the model's behavior, including on your own API or proxy.
- The selector shows only the levels that work: Off / On for models that can only be switched on or off, no "Off" for models that always reason, and no selector for models without reasoning.
- "Re-check the model" is in the reasoning menu.
