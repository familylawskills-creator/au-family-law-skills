# Getting started

These skills were written for Claude, and they also work on other AI tools such as ChatGPT, Gemini and Grok. Each one is a folder with a `SKILL.md` (instructions for the AI) and a `USER-GUIDE.md` (instructions for you).

Pick the part that matches your AI: part 1A for Claude, part 1B for any other AI.

## 1A. Install on Claude
1. [Download this repository as a zip](https://github.com/familylawskills-creator/au-family-law-skills/archive/refs/heads/main.zip) and unzip it.
2. In Claude, open **Settings, then Capabilities, then Skills** and upload the skill folders you want. (Menu names may change; check Claude's help centre if you cannot find it.)
3. Start a new chat. Claude loads a skill automatically when your request matches it, or you can name it: "Use the family-orders-compliance-check skill".

## 1B. Use on another AI (ChatGPT, Gemini, Grok and others)

Other AI tools have no "install skill" button, or have their own version of one. You give the AI the skill file in a chat instead.

1. [Download this repository as a zip](https://github.com/familylawskills-creator/au-family-law-skills/archive/refs/heads/main.zip) and unzip it.
2. Open the folder for the skill you want (see the table in part 2).
3. Start a **new chat** in your AI.
4. Upload the `SKILL.md` file from that folder. If the folder has a `references` folder, upload every file in it as well.
5. Paste this message and send it:

   > Review this skill. Rewrite any instruction that depends on a tool or feature you do not have, so it works with your own tools. Do not change the legal content, the checklists or the citations. List every change you made.

6. **Read the list of changes.** They should only be about tools and file formats, for example swapping one document tool for another. If the AI changed a rule number, a section number, a checklist item or a case name, tell it to undo that change.
7. Upload your documents in the same chat.
8. Ask your question and name the skill, for example: "Use the single-expert-report-review skill to review this report."

Tips for other AI tools:
- **One skill per chat.** Start a new chat for each skill and each matter, so the AI does not mix them up.
- **Turn on web search** if your AI has it. The skills tell the AI to check that the law is current.
- **If the AI skips steps or summarises**, say: "Follow the skill step by step and produce every output it lists."
- **If your AI can save custom instructions** (a custom GPT, a Gem or a project), you can put the adapted skill there so you do not have to upload it each time.
- **Expect a different look.** Another AI may give you a plain document instead of a Word or PDF file. The findings should be the same.

How well does it work? In November 2026 the single-expert-report-review skill was tested on two other AI tools with a fictional report containing 24 planted defects. Both found all 24. The other skills have not been tested this way.

## 2. Pick the right skill

| I want to... | Use |
|---|---|
| Check whether someone is following court orders or a child support agreement | `family-orders-compliance-check` |
| Challenge a single expert report, Child Impact Report or Family Report | `single-expert-report-review` |
| Review the Independent Children's Lawyer | `icl-transcript-review` |
| Review a solicitor (mine, my former one or the other side's) | `party-solicitor-conduct-review` |
| Write any of the above up as a complaint | `complaint-letter-format` |

## 3. Get a good result
1. **Upload the real documents.** The skills cite page and paragraph numbers and will not work from memory or summaries.
2. **Ask one narrow question.** One event, one statement or one report at a time.
3. **Answer the follow-up questions.** The skill asks for the single most useful missing document.
4. **Check the output.** Open every cited section and case. Fill in every square bracket.
5. **Take it to a lawyer** before you file, complain or act.

## 4. Stay safe
- **Not legal advice:** read `DISCLAIMER.md` before you use any skill.
- **Privacy:** section 114Q of the Family Law Act 1975 (Cth) makes publishing identifying details of family law proceedings an offence. Keep your reports private.
- **Before you upload a court report to any AI:** read the order that released the report to you. A court order can limit who may see a report. If it does, or you are not sure, ask a lawyer before uploading it anywhere.
- **Your orders:** if you have an injunction or communication order, never send an analysis to the other party.
- **Free help:** LawAccess NSW (1300 888 529), Legal Aid in your state, or a community legal centre.
