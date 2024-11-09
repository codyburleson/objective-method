---
created: 2024-11-09T01:23
modified: 2024-11-09T13:02
tags:
  - type/pattern/pkm
---

> [!warning] A.I. Draft
> Warning: this is only an initial draft produced by the Claude LLM for brainstorming purposes. Editing is required.

## Context

In personal knowledge management systems, users need to uniquely identify and link atomic notes in a way that supports both structured organization and organic growth. Traditional file naming and hierarchical systems can become limiting and don't effectively capture the relationships between ideas.

## Problem

How can we create a unique identification system for notes that supports non-hierarchical linking, maintains stability over time, allows for infinite growth, and provides useful contextual information without becoming overly complex?

## Forces

- Notes need stable, unique identifiers for reliable linking
- Sequential numbers alone don't provide contextual information
- Hierarchical numbering systems become rigid and break down
- Date-based systems provide temporal context but can be limiting
- IDs should be human-readable but concise
- System must scale to thousands of notes
- Users need to quickly identify note context from the ID
- Links should remain stable even as understanding evolves
- System should work across different tools and platforms

## Solution

Create unique identifiers for notes using a combination of:

1. Timestamp-based ID (YYYYMMDDHHmm)
2. Optional short descriptive suffix
3. Clear separation between ID and title

For example: 202311091435 or 202311091435a

The system provides:

- Guaranteed uniqueness through timestamps
- Chronological ordering by default
- Ability to branch (using letter suffixes)
- Platform-independent functionality
- Permanent addressability
- Context through optional descriptive elements

## Implementation

1. When creating a new note:
    - Generate timestamp in format YYYYMMDDHHmm
    - Add letter suffix if creating branch notes (a, b, c)
    - Separate ID from note title with space or delimiter
2. Use full ID when linking between notes
3. Maintain consistent formatting across all notes
4. Never change IDs once assigned
5. Keep IDs visible and easily accessible
6. Use system-wide search to locate notes by ID
7. Create index notes to organize groups of related IDs

## Examples

- Basic note: 202311091435 Writing techniques
- Branch note: 202311091435a Writing techniques - poetry
- Link format: [[202311091435]]
- Index note collecting multiple related IDs
- Structure note using IDs to create sequences
- Different tools implementing same ID format

## Resulting Context

- Reliable, permanent note addresses
- Freedom from hierarchical constraints
- Clear chronological development visible
- Easy branching of related ideas
- Platform independence
- Scalable to thousands of notes
- Supported linking and backlinking
- Preserved context through timestamps

## Related Patterns

- Atomic Notes
- Progressive Summarization
- Map of Content
- PARA Method
- Digital Garden
- Direct Link References
- Backlinks

## Known Uses

- Original Luhmann Zettelkasten
- Obsidian
- Roam Research
- The Archive
- Zettlr
- DEVONthink
- Personal wikis