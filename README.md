# sussy-ai-symbols

This is an empirical list of symbols that LLM tends to generate while human writers are not likely to use. An example would be em dash `—` ([def](https://en.wikipedia.org/wiki/Dash#Em_dash)). Therefore, they are typically a good rough indicator of LLM-generated text, or at least they will make the text looks suspicious. Besides the symbols, this doc also gives the alternative symbols that are commonly used by human.

These symbols are usually hard to type on a typical keyboard without using a special editor like Microsoft Word, which is why they are less used by human.

> Disclaimer: This list is very subjective. I'm not a native English speaker, and my usage of English is primarily restricted to reading and writing technical stuff, such as paper, textbook, post.

## How to use this doc?

- Write a python script that replaces the ai-likely symbols with human-likely symbols
- Prepend it to your prompt to LLM, so they won't use these symbols
- ...

## The list

Format
```
- <symbol name>
  - symbol: `<the actual symbol>`
  - human-ver: `<the more-likely-to-be-human alternative>`
  - empirical evidence:
    <an optional section that documents why I think this looks AI>
```

- em dash
  - symbol: `—`
  - human-ver: `-`
  - empirical evidence:
    Personal experience, and [this wiki page](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing#Overuse_of_em_dashes)

