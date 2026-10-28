# AI tool usage

This was written by hand.

## Tools

### Platforms

- Claude code and web
- Cursor agent
- ChatGPT web
- Duck AI

### Models

Usually latest versions, but as of writing I am using: (depending on context, project and tool)

1. Claude Sonnet 5.5
2. Claude Haiku 5.5
3. Claude Opus 5.5
4. Grok 4.6
5. Grok 4.7
6. GPT-Live-1.1 Quip
7. GPT-6 Luna

The above list contains the models I consciously use on a somewhat regular basis at the time of writing, ranked somewhat by usage amount.
The models I use at any exact moment mostly depend on what the platforms mentioned above provide at said given moment.


## Documentation
The presence of documentation always depends on the project, minor projects may have worse documentation. This especially applies in the beginning of development, before I have decided which kind of project it actually is.

### AI use degrees

#### Frequently documented AI use:
`"Vibe" coding`: AI generates code, and it gets minimal or no review.

`"Agentic" coding`: `Vibe` coding, but with a plan, rules and usually a significant increase in review and testing. 

#### Usually undocumented AI use:
`"Partially" AI coded`: AI generated code is only used when necessary, and thoroughly reviewed and tested before use.
Code is still written by hand, and AI inclusions are used when it makes sense.

`AI "assisted"`: AI generated code is at WORST copied after very thorough and careful review and testing, however the workflow is mainly using AI for boilerplating, review, explanations, examples, etc. 
Anything that is not logic executing code, can be AI generated.

`AI "tutored"`: AI never knows what exactly is being made, it is used to find methods and tools, or explain concepts.
It functions more like a tutor or search engine rather than a coder.

#### Usually documented *lack* of AI use:
`AI "free"`: AI is avoided. 
If AI is used at all, then it NEVER generates code and is only a pointer in the right direction at worst. 

### Documentation methods

#### Model commit authoring:
Fully `vibe` coding, maybe slightly irresponsible `agentic` coding

#### Model co-authoring commit:
Anything from severly AI `assisted` to `vibe` coding

#### Mention in comments or README:
Sometimes implicit or specified AI use degree, often thoroughly reviewed, that means AI `assisted` or worse.

### Mentality/Goal
As a student I want to learn most efficiently, and I believe rampant AI use will halt my functionality as a human. 
Therefore I try to do AI `free` projects, and increase my amount of AI `free` work.

At the same time being efficient means taking shortcuts when necessary, therefore much of my work is AI `tutored`.
For the same reason, I use AI `assisted` coding when I consider my proficiency is high enough that future learning will not be impaired by the increase of AI use.
Sometimes this wanders over into `partially` AI coded or even `agentic` coding territory, but that is exceptions rather than the rule, and is usually done in situations where I am testing ideas or doing uninteresting work.

However I still often `vibe` code for inspiration or quick setups when I have deadlines. This is usually followed up with a more AI `assisted` workflow to fix, reimplement, update or learn from the `vibe` coded project.

Some projects demand `vibe` or `agentic` coding, in such cases it is often very obvious. Whether it is a good idea or not, is not my decision in such cases.

On the other hand, some projects demand no AI written commits, meaning anything even vaguely beyond AI `assisted` code will never be merged.
