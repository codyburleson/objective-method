---
created: 2024-11-09T01:26
modified: 2024-11-09T13:02
tags:
  - type/pattern/pkm
---

> [!warning] A.I. Draft
> Warning: this is only an initial draft produced by the Claude LLM for brainstorming purposes. Editing is required.

## Context

Knowledge workers collect large amounts of text-based information (articles, books, notes) but struggle to quickly recall and make use of this content later. Traditional highlighting or summarization alone often results in either over-highlighting or loss of important context.

## Problem

How can we process and layer information in a way that makes future review efficient while preserving important context and supporting different levels of detail needed for different use cases?

## Forces

- Full text contains important context but is time-consuming to review
- Single-pass highlighting often captures too much or too little
- Different use cases require different levels of detail
- Initial processing time needs to balance with future review value
- Important insights can be lost in summarization
- Pure summaries lose supporting evidence and context
- Users need quick ways to assess relevance
- Processing should support future synthesis and creation
- Time available for review varies by situation

## Solution

Layer information through progressive rounds of highlighting/summarization:

1. Layer 0: Original, full-text content
2. Layer 1: Bold the most important 10-20% of content
3. Layer 2: Highlight the most important 10-20% of the bolded content
4. Layer 3: Create a summary note in the margins
5. Layer 4: Executive summary at the top

Each layer:

- Builds on previous layers
- Increases information density
- Supports different review speeds
- Preserves context through layer accessibility
- Can be added when needed, not all at once

## Implementation

1. Capture original content completely (Layer 0)
2. During first read, bold key points and passages (Layer 1)
3. Review bolded content and highlight crucial elements (Layer 2)
4. Add margin notes for key insights/connections (Layer 3)
5. Create brief executive summary if needed (Layer 4)
6. Add layers progressively as content proves valuable
7. Use appropriate layer for different review needs

## Examples

- Article review with 4 layers of processing
- Book notes with progressive highlighting
- Meeting notes with layered summaries
- Research paper annotations
- Course notes with multiple review layers
- Project documentation with progressive detail

## Resulting Context

- Quick assessment of note relevance
- Multiple entry points for review
- Preserved context when needed
- Efficient future retrieval
- Support for different use cases
- Progressive investment in valuable content
- Improved retention through layered processing
- Better synthesis of information

## Related Patterns

- Zettelkasten
- Map of Content
- PARA Method
- Atomic Notes
- Evergreen Notes
- Fleeting Notes
- Literature Notes

## Known Uses

- Tiago Forte's note-taking system
- Digital note-taking apps
    - Evernote
    - Notion
    - Roam Research
    - Obsidian
- Research workflows
- Reading note systems
- Study methods

Would you like me to elaborate on any particular aspect of Progressive Summarization or explain how it complements the other patterns we've discussed?