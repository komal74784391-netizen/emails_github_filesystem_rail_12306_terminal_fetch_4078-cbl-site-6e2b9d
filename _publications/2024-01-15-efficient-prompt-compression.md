---
title: "Efficient Prompt Compression for Long-Context Summarization"
collection: publications
category: manuscripts
permalink: /publication/efficient-prompt-compression
excerpt: "A token-level compression model that keeps summary-relevant spans while shrinking long prompts for efficient inference."
date: 2024-01-15
venue: "Transactions of the Association for Computational Linguistics"
paperurl: "https://doi.org/10.1162/tacl_a_00631"
citation: "Bennett, C., Okafor, R., and Lindqvist, M. (2024). Efficient Prompt Compression for Long-Context Summarization. Transactions of the Association for Computational Linguistics, 12, 441-457."
codeurl: "https://github.com/komal74784391-netizen/emails_github_filesystem_rail_12306_terminal_fetch_4078-cbl-code-6e2b9d/tree/main/packages/prompt-compression"
---

Long prompts dominate the cost of summarization systems. We train a small compressor that removes tokens with low summary relevance and show that it preserves ROUGE scores at a fraction of the prompt length, even for inputs that exceed the base model's context window.
