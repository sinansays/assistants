# assistants
Custom instruction prompts for LLM assistants/bots/GPTs

## purpose

This repository is dedicated to sharing and openly documenting custom assistants built on top of LLMs (primarily for OpenAI's 'GPTs' at the moment). These assistants are tailored to specific tasks, enhancing productivity and decision-making by tapping into the extensive world knowledge embedded in these models.

These specialized assistants can perform retrieval-augmented generation (RAG) and automate tasks, thereby extending the capabilities of foundational models to suit personal or organizational needs. However, one significant limitation remains—the lack of transparency in sharing the custom instruction prompts and configurations that drive these tailored interactions.

In the spirit of open knowledge and collaboration, this repository aims to bridge that gap. By publicly documenting and sharing the custom instructions and configurations, it ensures transparency and fosters a community where shared knowledge leads to enhanced utility and innovation across various applications.

[Echoing the perspective of Simon Willison](https://simonwillison.net/2023/Nov/15/gpts/), it is anticipated that the details of how we configure and interact with these assistants might eventually become public knowledge (through prompt injection or otherwise). Therefore, instead of guarding these prompts as proprietary secrets, I am embracing openness. Sharing custom prompts can help contribute to a broader understanding and improvement of custom LLM assistant usage.

Through this repository, I invite collaboration, feedback, and contributions from all, ranging from enthusiasts to experts, to refine and expand the capabilities of custom LLM assistants. The goal is to build effective tools in a manner that is openly accessible and beneficial to the community at large.

## directory

- [VoiceEntryGPT](https://chatgpt.com/g/g-iLWRNBYhs-voiceentrygpt)
    - Transforming voice memos into structured, well-written entries based on detecting the type of content the speaker dictated
- [Q&A GPT (CoT)](https://chatgpt.com/g/g-RjIuXBfT9-q-a-gpt-cot)
    - Provides guidance across an array of topics via focused and iterative Q&A, using chain-of-thought reasoning to deliver comprehensive insights
- [Dilemma Solver (CoT)](https://chatgpt.com/g/g-oICjNekeF-dilemma-solver-cot) [fork of 'Q&A GPT']
    - Assists over-thinkers with quick decisions via focused and iterative Q&A, using chain-of-thought reasoning to guide towards informed conclusions
- [EmojiBot](https://chatgpt.com/g/g-lMRjCSY0T-emojibot)
    - Translates text into relevant emoji (with configurable parameters)
- [Document Explorer](https://chatgpt.com/g/g-cMTPwsi84-document-explorer)
    - Explore uploaded PDF documents by asking questions through RAG
- [IkigaiBot](https://chatgpt.com/g/g-48mAewl6P-ikigaibot)
    - Your career and life coach, helping you find balance and purpose through the Ikigai framework
- [Legal Review GPT](https://chatgpt.com/g/g-Lj9iohC1Y-legal-review-gpt)
    - Analyzes and highlights critical clauses and terms in legal documents to inform and guide potential parties to said documents
- [PM Assistant](https://chatgpt.com/g/g-dsxwNwy5w-pm-assistant)
    - Generalist jack-of-all-trades product management assistant

## licensing

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
