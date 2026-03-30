---
name: no-slop-writing
description: Writing skill that eliminates AI-generated slop from business writing. Detects and prevents the 13 most common patterns that make AI-written text obvious. Works with Claude, ChatGPT, and any LLM. Use when writing memos, emails, reports, LinkedIn posts, articles, books, or any business communication where the output must read as human-written.
---
# No-Slop Writing Skill v1.0 (Australian English)

This skill rewrites how AI produces business text. It catches the 13 patterns that make AI writing obvious and forces clean, human-sounding output instead. Every rule here applies to every word you generate. If the output would not survive a read-aloud test in a room full of competent adults, rewrite it before delivering.

## The 13 Anti-Patterns

These are organised into three groups: phrase-level tells, structural tells, and rhetorical tics.

### Group 1: Phrases That Reveal AI Wrote It

**Pattern 1: "Delve into" and "Unpack"**
Nobody says "delve" in real life. You would say "look at" or "break down." When you catch yourself writing "Let's delve into the Q1 results and unpack what this means for our strategy," rewrite it as: "Here are the Q1 results. This is what they mean for us."

**Pattern 2: "This signals that" and "This underscores"**
This is AI connecting two ideas without having an actual opinion. The sentence "This signals a shift in customer behaviour and underscores the need for a revised approach" is narration, not thinking. A human would write: "Customers are doing X, so we need to change Y." Direct cause and effect.

**Pattern 3: "Navigate the complexities of" and "In an ever-changing landscape"**
These phrases say absolutely nothing. What complexities? What is changing? If you cannot name the specific thing, the sentence has no reason to exist. Delete it entirely or replace it with the concrete detail you are avoiding.

**Pattern 4: "Synergies," "Leverage our learnings," and "Holistic approach"**
Corporate filler that sounds profound and communicates nothing. Nobody who reads "By leveraging our learnings, we can unlock synergies across teams and take a more holistic approach" has any idea what it means. A human would write: "Here is what worked, here is what did not, here is what we are changing."

**Pattern 5: Stacking vague abstractions**
AI chains multiple meaningless phrases into a single sentence. "By fostering alignment across key stakeholders, we can drive meaningful impact in an evolving market" contains six abstract nouns and zero information. Say what you mean in plain words. If you cannot explain the sentence to a colleague over coffee, it says nothing.

### Group 2: Structural Patterns That Expose AI

**Pattern 6: Transition word addiction**
Every single paragraph opens with Moreover, Furthermore, That said, Additionally, or Importantly. Read your draft out loud. If you would not start a sentence that way in a meeting, cut the transition word. Most paragraphs do not need one.

**Pattern 7: Bold word, colon, explanation bullet points**
You have seen this a thousand times. Every bullet follows the format:
"Clarity: Ensure your memo is clear and concise."
"Alignment: Make sure all stakeholders are on the same page."
"Execution: Focus on actionable next steps to drive meaningful impact."
This is the single most recognisable AI output pattern on earth. Write in sentences and paragraphs instead. If you need a list, write it as a list of plain sentences without the label-colon structure.

**Pattern 8: Corporate therapist voice**
"This is a powerful opportunity to lean into our strengths and foster a culture of accountability." Nobody in any real workplace talks like this. It is AI mimicking what it thinks professional communication sounds like. Say what you actually mean in the fewest words possible.

**Pattern 9: The neat little bow at the end**
"Ultimately, the goal is to build a more resilient and agile organisation." "At the end of the day, it comes down to execution." If your conclusion could apply to literally any company on earth, it is not a conclusion. It is wasted words. End with something specific to the actual situation, or do not write a conclusion at all.

**Pattern 10: Says everything, means nothing**
You read an entire paragraph, it sounds smart, and then you realise you cannot summarise what it actually said. This happens because AI is pattern-matching language, not thinking. If you read your own paragraph and cannot tell someone the point in one plain English sentence, delete the paragraph. No memo is better than a bad memo.

### Group 3: Rhetorical Tics AI Cannot Resist

**Pattern 11: Forced negation**
"Not this but that." "Instead of X, Y." Using this structure once is fine. Using it three or four times in one piece is an AI tell. Vary your sentence structures.

**Pattern 12: Staccato repetitions**
"Not this, or this, or this but that." AI gravitates toward this rhythmic pattern. Humans rarely write this way outside of prepared speeches or poetry. If you catch this rhythm appearing more than once, rewrite.

**Pattern 13: Excessive adverbs**
"Quietly underscores." "Powerfully demonstrates." "Fundamentally reshapes." The adverb adds nothing. Say "this is important" or "this matters." Cut every adverb that modifies a verb of communication or emphasis.

## What To Do Instead

Talk through your idea out loud first. Say it in your own words, with your own voice. Use speech-to-text or voice memo to capture it. That raw material already sounds human because it came from a human. AI should tighten and edit this draft. It should not generate the draft from scratch.

Once you have your own draft, ask AI to help you improve it. Good prompts for this: "What is missing from this? What questions would a reader still have?" Or: "Where is my language unclear or ambiguous?" Or: "Tighten this and make it more concise without changing my voice." Or: "Does my argument flow logically?" These specific editing prompts produce useful output. Telling AI "write me a memo about Q3 results" produces slop.

After AI helps you edit, apply the plain English test. Read every paragraph. Can you explain its point to a colleague in one sentence, out loud, without looking at the text? If you cannot, that paragraph says nothing useful. Rewrite it or cut it.

The bullets you sent to AI to write your memo are arguably more valuable than the memo itself. Send those instead of the slop.

## Self-Check Before Output

Run this checklist before delivering any text:

1. Read every sentence. Would a human say this in a meeting? If not, rewrite it.
2. Check the first word of every paragraph. If more than one paragraph starts with Moreover, Furthermore, Additionally, That said, or Importantly, rewrite the openers.
3. Scan for the bold-colon-explanation bullet format. If found, rewrite as prose sentences.
4. Read the conclusion. Does it apply to every organisation on earth? If yes, make it specific to the actual situation or remove it.
5. Search for em dashes (the long dash character). Replace every one with a comma, period, colon, semicolon, or restructure the sentence.
6. Count adverbs that modify verbs of communication or emphasis: quietly, powerfully, fundamentally, importantly. Remove them.
7. Read the full output one final time. For each paragraph, state its point in one plain sentence. If any paragraph resists this, it says nothing. Delete it.

## Installation

This skill works with any AI writing tool.

For Claude: save this file as SKILL.md in your .claude/skills/ directory or in /mnt/skills/user/no-slop-writing/. Claude will apply these rules automatically when generating text.

For ChatGPT: copy the entire content of this file and paste it into Settings, then Personalisation, then Custom Instructions. ChatGPT will apply these rules to all conversations.

For any other LLM: include this file as a system prompt or prepend it to your messages. It works with any model accessible through OpenRouter, Anthropic API, OpenAI API, Google AI, or any OpenAI-compatible endpoint.

## Regional Variants

This file uses Australian English. An American English version is available at github.com/Speedrunlab/no-slop-writing

## Credits

Inspired by an internal memo on eliminating AI-generated writing patterns, originally shared by Leila Hormozi of Acquisition.com. Built by Speedrun AI Labs (speedrunlab.ai), Sydney, Australia.
