# Agent Guidelines: L2 Lyric Implementation

This document outlines the standard for implementing and refactoring lyrics within this library. Agents should follow these principles to ensure a consistent, reader-focused experience.

## 1. L2 (Target Language) Standards
- **Original Script**: Use the script originally used by the artist. Traditional Chinese for artists from Taiwan/Hong Kong; Simplified Chinese for artists from Mainland China.
- **Purity**: No Pinyin, no HSK levels, and no emojis in the lyrics. The focus is on the poetic form of the characters.
- **Soul & Context**: Preserve significant portions of the original performance (intros, iconic choruses, and bridges). The goal is a song, not a vocabulary list.

## 2. L1 (Reference Language) Standards
- **Full-Sentence Translation**: Provide natural, evocative translations rather than direct word-for-word substitutions.
- **Minimalism**: Focus on the core imagery. Avoid extra examples or "HSK-style" fluff. Leave room for the reader's imagination.

## 3. Highlighting System (`hX` Spans)
- **Parallel Spans**: Use `<span class="h1">`, `<span class="h2">`, etc., to link interesting phrases in the L2 text to their corresponding meaning in the L1 text.
- **Selective Mapping**: Highlight key phrases, idioms, or beautiful imagery that a learner might want to look closer at. 
- **Consistency**: Ensure the `hX` ID in the L2 string matches the exact meaning and ID in the L1 string.

## 4. Frontmatter Standards
- **Title**: Original song name (with common English name in parentheses if available).
- **Artists**: Always format as `(Chinese Name | English Name)` – e.g., `(告五人 | Accusefive)`.
- **YouTube**: Use high-quality official music videos or official lyric videos.
