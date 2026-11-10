Mole Code 1.2.2 (PC) / 1.2.6 (Android)
- Android: Mole checks every loaded model of the provider in the background (the current one first), including your own API. When you pick a model the result is already known.
- Android: the reasoning selector appears only if the check confirmed that reasoning really works for that model. No guessing by model name.
- Android: hidden reasoning is detected too. If the server hides the model's thoughts (common for Claude through proxies), Mole compares how many tokens and how much time the model spends with and without the parameter.
- Android: the model list marks models that reason ("Reasoning: levels" or "on / off"). Refreshing the list re-checks all models.
- PC 1.2.2: reasoning is detected by a real check, and the selector shows only the levels that work.
