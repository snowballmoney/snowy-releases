# Changelog

What changed in each Snowy release, newest first. The installers are on the [Releases](https://github.com/snowballmoney/snowy-releases/releases) page.

## 0.1.0-rc3 · 2026-08-24

The meeting assistant gets two speeds, and each chat knows what it should, including facts that changed after a note was written.

- Fast answers come straight from the meeting; Thinking takes longer and also searches your past notes, naming the ones it used.
- A Fast answer offers Check past notes, which asks the same question again in Thinking mode.
- A note's chat knows when something in it was changed in a later meeting, and says so instead of quoting the old fact.
- The main chat knows both what you owe people and what they promised you.
- A space or folder chat focuses on the open items in its own notes.
- Chatting in a very long meeting note no longer resends the whole transcript with every message.
- Fixed on macOS: the window buttons no longer cover the section title.
- Fixed: buttons that open Settings on a particular page land on that page.

## 0.1.0-rc2 · 2026-08-21

The meeting panel becomes the place where the meeting happens, local captions get much faster, and Home says plainly what Snowy can do.

- Starting a meeting opens a side panel with a suggested line, a short live transcript and a question box. It stays out of screen shares.
- Suggestions are ready when the other side stops talking, drawn from the meeting so far and your past notes.
- Ask during the call: answers come from the live meeting first, then your notes, and name the notes they used.
- Local captions now arrive word by word instead of a sentence at a time, labelled You and Others.
- Transcription setup has a Basic mode that picks and downloads the right model for your computer.
- A card on Home says what works now and what still needs an AI model.
- "Note Formatting" in Settings is now called Actions.
- Fixed: discarding a meeting no longer writes it up first, and saving without an AI model no longer interrupts you with a setup prompt.
- Fixed: buttons that open a Settings page land on that page, and the transcript no longer scrolls away from what you were reading.

## 0.1.0-rc1 · 2026-08-19

The first release candidate carrying the Snowy name. This was the first version of the app, which was later rebuilt from rc11 on.

- Records your microphone and the computer's sound separately, so both sides of a call are captured without a bot joining the meeting.
- Notices meetings when Zoom, Teams, Webex or FaceTime opens, when the microphone goes live for a browser call, or from your calendar, and asks before recording.
- Keeps the 45 seconds before you accept, so a meeting doesn't start mid-sentence.
- Transcribes on your computer by default, in 58 languages; cloud transcription is optional, with your own API key.
- Writes notes when you stop recording: a summary, decisions and action items.
- Search finds meetings by meaning, not only by exact words, and a chat assistant answers across your notes with links to its sources.
- Remembers decisions, commitments and people across meetings, and keeps them up to date as they change.
- Works with Google, Microsoft and Apple calendars, with notes linked to their events.
- No account and no telemetry; your API keys are stored securely on your computer.
- Builds are not signed yet, so Windows and macOS warn on first launch.

## 0.1.0-rc.6 · 2026-08-14

The same app as rc.5, published again so it could be tested on Intel Macs as a release of its own.

- Installers for Windows and for Apple Silicon and Intel Macs.
- No changes to the app since rc.5.

## 0.1.0-rc.5 · 2026-08-13

A test build with an installer for each kind of computer.

- Installers for Windows and for Apple Silicon and Intel Macs, all from the same build.
- The installers are not signed yet.

## 0.1.0-rc.4 · 2026-08-13

This was a test build of Snowy's first version (then called Snowi), and the first one to include a Mac installer.

- A Mac installer alongside the Windows one, for testing only.
- The installers are not signed yet.
