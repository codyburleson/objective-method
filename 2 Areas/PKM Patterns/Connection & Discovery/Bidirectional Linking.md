---
created: 2024-11-09T01:39
modified: 2024-11-09T13:03
tags:
  - type/pattern/pkm
---

> [!warning] A.I. Draft
> Warning: this is only an initial draft produced by the Claude LLM for brainstorming purposes. Editing is required.

## Context

In knowledge management systems, relationships between ideas are often as important as the ideas themselves. Traditional one-way links (like in traditional websites) fail to capture the full web of relationships between notes and make it difficult to discover unexpected connections.

## Problem

How can we create and maintain connections between notes that reveal both explicit and implicit relationships, support serendipitous discovery, and help users understand the broader context of their knowledge?

## Forces

- Ideas naturally reference other ideas
- Connections may be relevant in both directions
- Manual tracking of references is time-consuming
- Relationships between notes evolve over time
- Users need to see both incoming and outgoing connections
- Context of connections matters
- Network effects increase with more bidirectional links
- Traditional one-way links miss half the relationship

## Solution

Implement a system of bidirectional linking where:

1. Every link created from Note A to Note B automatically creates a reverse link
2. Both notes display their incoming and outgoing links
3. Links are easily created using standard notation (e.g., \[\[Note Title\]\])
4. Backlinks are automatically tracked and displayed
5. Context snippets show how notes reference each other
6. Links can be annotated with relationship type or context

## Implementation

1. Use consistent linking syntax (e.g., \[\[Note Title\]\])
2. Display backlinks section in each note
3. Show context snippets for backlinks
4. Enable easy navigation in both directions
5. Regularly review backlinks for insights
6. Use backlinks to discover connections
7. Consider relationship types in link context

## Examples

- Note A links to Note B, creating automatic backlink
- Daily notes linking to concept notes
- Project notes linking to resource notes
- Literature notes linking to atomic concepts
- Meeting notes linking to action items
- Research notes linking to sources

## Resulting Context

- Rich network of visible connections
- Serendipitous discovery of relationships
- Easier navigation between related ideas
- Emergent structure through links
- Reduced manual maintenance
- Better context awareness
- Enhanced knowledge retrieval
- Supported idea development

## Related Patterns

- Atomic Notes
- Knowledge Graph
- Concept Clustering
- Map of Content
- Trail Marker
- Emergence Board

## Known Uses

- Roam Research
- Obsidian
- LogSeq
- TiddlyWiki
- Athens Research
- Research databases
- Personal wikis