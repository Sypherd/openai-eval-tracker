# OpenAI Eval Tracker

With the significant improvements that come with GPT-4, there is massive demand for access to the API. There is a waitlist [here](https://openai.com/waitlist/gpt-4-api), but there's no guarantee of when access will be granted. OpenAI has provided a way to get earlier access, however, through contributions to its recently open-sourced Evals repo (see [this note](https://openai.com/waitlist/gpt-4-api#:~:text=During%20the%20gradual,Access%20Program.) and [this article](https://techcrunch.com/2023/03/14/with-evals-openai-hopes-to-crowdsource-ai-model-testing/)). The standards are vague, noting that access will be granted to "exceptional model evaluations." A little more information can be found [in the PR template](https://github.com/openai/evals/blob/main/.github/PULL_REQUEST_TEMPLATE.md). Looking at the active PRs and which ones have been accepted, there seems to be little feedback on the quality of a submission, and the ones that are accepted appear to be the ones that the models perform poorly on and the moderators deem "interesting" or "clever" (see [this comment](https://github.com/openai/evals/pull/302#pullrequestreview-1349533532), [this comment](https://github.com/openai/evals/pull/112#pullrequestreview-1344881565), or [this comment](https://github.com/openai/evals/pull/239#pullrequestreview-1344890191)). Some PRs sit for days while others are approved almost immediately.

To help people that are looking for inspiration for good Evals and to make sure they don't work on one that has already been merged, I decided to create this repo that tracks all of the Evals that have been accepted by OpenAI. I will update twice a day, at around 14:00 GMT and 02:00 GMT.

## Accepted Evals
Format: \<date-merged\> \<short-title\>: \<link-to-PR\>

* 4/21 Utility Charge: https://github.com/openai/evals/pull/735
* 4/21 Unified Patch: https://github.com/openai/evals/pull/537
* 4/21 Emoji Riddle: https://github.com/openai/evals/pull/510
* 4/21 Japanese License: https://github.com/openai/evals/pull/719
* 4/21 Spider Text-to-SQL: https://github.com/openai/evals/pull/72
* 4/21 Loss Logic: https://github.com/openai/evals/pull/82
* 4/21 Amateur Radio: https://github.com/openai/evals/pull/516
* 4/21 General Science: https://github.com/openai/evals/pull/641
* 4/21 Physical Rotation: https://github.com/openai/evals/pull/691
* 4/20 Music Theory: https://github.com/openai/evals/pull/725
* 4/20 Russian Medical: https://github.com/openai/evals/pull/530
* 4/14 Mongolian World Knowledge: https://github.com/openai/evals/pull/338
* 4/13 Financial Math: https://github.com/openai/evals/pull/566
* 4/13 Escher Sentences: https://github.com/openai/evals/pull/393
* 4/12 Moral Exception: https://github.com/openai/evals/pull/534
* 4/11 Logical Reasoning: https://github.com/openai/evals/pull/470
* 4/11 Swedish Spelling: https://github.com/openai/evals/pull/583
* 4/11 Heart Disease: https://github.com/openai/evals/pull/538
* 4/11 Emotional Intelligence: https://github.com/openai/evals/pull/589
* 4/11 Brazilian Lexicon: https://github.com/openai/evals/pull/608
* 4/10 Malicious Strings: https://github.com/openai/evals/pull/627
* 4/4 Russion Hallucination: https://github.com/openai/evals/pull/157
* 3/29 Bulgarian Lexicon: https://github.com/openai/evals/pull/508
* 3/28 Forth Stack 2.0: https://github.com/openai/evals/pull/449
* 3/28 Illinois Law: https://github.com/openai/evals/pull/486
* 3/28 Chinese to Arabic Numbers: https://github.com/openai/evals/pull/443
* 3/28 Manga Translation: https://github.com/openai/evals/pull/319
* 3/27 Tax Liability: https://github.com/openai/evals/pull/454
* 3/27 Mendelian Inheritance: https://github.com/openai/evals/pull/444
* 3/27 Text Date: https://github.com/openai/evals/pull/67
* 3/27 Russian Exam: https://github.com/openai/evals/pull/127
* 3/27 Complex Numbers: https://github.com/openai/evals/pull/223
* 3/27 Crossword Clues: https://github.com/openai/evals/pull/358
* 3/27 Ukrainian Universities: https://github.com/openai/evals/pull/329
* 3/27 Heavier Item: https://github.com/openai/evals/pull/396
* 3/27 Regex Match: https://github.com/openai/evals/pull/159
* 3/26 Stock Options: https://github.com/openai/evals/pull/334
* 3/26 Logic Statements: https://github.com/openai/evals/pull/366
* 3/26 ROT13 Strings: https://github.com/openai/evals/pull/361
* 3/26 Sarcasm Detection: https://github.com/openai/evals/pull/56
* 3/26 Tort Law: https://github.com/openai/evals/pull/236
* 3/22 Multiple Actors: https://github.com/openai/evals/pull/272
* 3/22 Rhyming (Hebrew): https://github.com/openai/evals/pull/176
* 3/22 Poker Hands: https://github.com/openai/evals/pull/299
* 3/22 Forth Stack: https://github.com/openai/evals/pull/351
* 3/22 Formal Logic: https://github.com/openai/evals/pull/53
* 3/22 First Letters: https://github.com/openai/evals/pull/346
* 3/21 Belarusian Lexicon: https://github.com/openai/evals/pull/372
* 3/21 Diagrammatical Reasoning: https://github.com/openai/evals/pull/341
* 3/21 Replace Characters: https://github.com/openai/evals/pull/324
* 3/21 Casual Reasoning: https://github.com/openai/evals/pull/257
* 3/21 Playing Chess: https://github.com/openai/evals/pull/45
* 3/21 Color Conversions: https://github.com/openai/evals/pull/46
* 3/21 Connect Four: https://github.com/openai/evals/pull/49
* 3/21 Cipher Decryption: https://github.com/openai/evals/pull/58
* 3/21 CS Theory: https://github.com/openai/evals/pull/83
* 3/21 Determinant Calculation: https://github.com/openai/evals/pull/92
* 3/21 Legal Ethics: https://github.com/openai/evals/pull/95
* 3/21 Anagrams: https://github.com/openai/evals/pull/192
* 3/20 Latitude and Longitude: https://github.com/openai/evals/pull/137
* 3/20 Halting Problem: https://github.com/openai/evals/pull/86
* 3/20 Nth Word: https://github.com/openai/evals/pull/27
* 3/20 Counting Bigrams: https://github.com/openai/evals/pull/302
* 3/16 Japanese Humor: https://github.com/openai/evals/pull/260
* 3/16 Pattern Identification: https://github.com/openai/evals/pull/71
* 3/16 Born First: https://github.com/openai/evals/pull/112
* 3/16 Chemical Equations: https://github.com/openai/evals/pull/240
* 3/16 Chess Pieces Left: https://github.com/openai/evals/pull/239
* 3/16 Electronic Components: https://github.com/openai/evals/pull/170
* 3/16 Cube Packing: https://github.com/openai/evals/pull/158
* 3/14 Reverse String: https://github.com/openai/evals/pull/1
