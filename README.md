# Charlando

A simple workspace for practicing spoken Spanish with an AI tutor that remembers previous conversations.

Talk about your life, explore a topic, or try a real-world situation. The tutor adapts to your level, offers gentle corrections, and saves useful observations in plain Markdown files. No written assignments, mandatory drills, or homework.

## Start a conversation

1. Clone this repository:

   ```sh
   git clone https://github.com/dmappel/charlando.git
   cd charlando
   ```

2. Open the folder in an AI assistant that can read and edit local files. Use its voice interface for spoken practice. If it does not automatically read `AGENTS.md`, ask it to read that file first.
3. Say **"Let's start"**, or the equivalent in any language you prefer.
4. Have a conversation. The first session introduces you to the tutor and provides a tentative assessment through conversation, without a written test.
5. Say **"That's all for today. Save my progress."** The tutor writes a short session note and updates the relevant learning files.

You do not need to fill in the files or know your level before starting. There is nothing to install inside this repository: it contains instructions and learning notes, not an application. You supply the AI assistant and voice interface; their availability and any costs depend on the tool you choose. A chat without access to this folder cannot automatically save your progress here.

## Your language, your pace

Spanish is the language you practice. You can ask questions, request explanations, or describe a missing word in **any language you are comfortable using**. The tutor uses that language for support when it can, clarifies when uncertain, and helps you return to Spanish at a comfortable pace. English is not a prerequisite.

The tutor learns your preferred support language, interests, correction preferences, and Spanish variety during conversation. Nothing is preset about your name, background, location, or ability. Valid regional Spanish is welcome.

Start with a few words or have a longer conversation. Ask the tutor to slow down, repeat, change the topic, or correct you more or less often. Useful expressions and recurring difficulties return naturally in later conversations.

## What the files do

| File | Purpose |
| --- | --- |
| `AGENTS.md` | Instructions for the tutor. |
| `PROFILE.md` | Your goals, preferences, and tentative assessment. |
| `PROGRESS.md` | Evidence of what is becoming easier and what still needs practice. |
| `MISTAKES.md` | Useful recurring difficulties, corrections, and follow-up observations. |
| `VOCAB.md` | Words and expressions you needed in conversation. |
| `CURRICULUM.md` | Two or three flexible speaking goals based on actual sessions. |
| `sessions/` | Short dated session notes, not full transcripts. |

Repository instructions, headings, and summaries are in English. Spanish examples and original learner phrases stay in their original language. Spoken explanations follow the learner's language preference.

## Saving and continuing

Use one personal clone per learner. At the start of the next session, the tutor reads the saved files and continues from there, including in a new chat with access to the same folder.

Ask to save before closing the voice interface. Closing it abruptly may leave a conversation unsaved. The tutor can only record content it actually received and should confirm saving only after checking the files.

Saving edits the local files; it does not automatically commit or push them. You can keep your learning history in Git when you want. Once filled in, these files contain personal learning notes: keep them in your own local copy or private repository rather than submitting them to this shared starter repository.

## Assessment limits

The initial level is tentative and becomes more useful with additional conversations. The tutor should distinguish independent answers from answers given with help.

A transcript can support observations about vocabulary and grammar, but it cannot reliably reveal pronunciation, intonation, pauses, or speaking speed. Those require appropriate audio access. Transcription artifacts should not become recorded learner errors, and uncertain corrections should be checked before they are reused.
