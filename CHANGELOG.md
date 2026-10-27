# Changelog

What changed in each Snowy release, newest first. The installers are on the [Releases](https://github.com/snowballmoney/snowy-releases/releases) page.

## 0.1.0-rc21 · 2026-10-27

A small release: a greeting by name, and fixes for some Claude answers and some PDFs. Everything else is as in rc20.

- The title bar greets you by name; click it to change the name. It isn't an account.
- Fixed: with a Claude plan or an Anthropic key, an answer Snowy couldn't read is asked for once more, and if that fails too you get a plain message instead of a technical error.
- Fixed: a PDF the reader couldn't handle is now read page by page another way, and Snowy says what it couldn't read.
- The knowledge base is marked as a beta in Settings › Snowy Brain. Documents stay on your computer.

## 0.1.0-rc20 · 2026-10-26

Snowy Brain gets a knowledge base, recaps are shorter by default, the follow-up email proposes the people invited, and Snowy tells you when an update is ready.

- Knowledge base: add PDF, Word, PowerPoint, text or Markdown documents in Settings › Snowy Brain. Answers can draw on them and cite the page or slide. Documents stay on your computer.
- Web research for typed questions with OpenRouter or a ChatGPT plan, off by default. Only search words go to the search, never the meeting.
- Ask the assistant questions before a meeting starts.
- With Snowy Brain on, questions know your meetings and your calendar for the coming week.
- People in Snowy Brain keeps one name per email address, learned from invitations or given by you.
- Recaps are Brief by default, with Standard and Detailed in Settings › AI › Recaps.
- Share › Email participants proposes the people invited, signed with the name you give in setup; check it, then send it from your mail app.
- Stop any answer while it is being written.
- An update notice at the foot of the main window; nothing restarts during a meeting.
- Speaker labels (beta, off by default) tell the voices on the other side apart as Speaker 1, 2, 3, and you can name them.

## 0.1.0-rc19 · 2026-10-20

Setup and the first meeting explain themselves, Snowy has one mark everywhere, and meeting memory now helps every action.

- The dock says Listening, Paused or Problem in words, and the status card says whether the audio is being saved.
- When a meeting ends, a Meeting saved card shows how the recap stands, with Open recap or Set up AI.
- Your first meeting opens on a short checklist that ticks as you go.
- Setup shows accounts and keys first, then offers to connect Google Calendar.
- One Snowy mark everywhere: in the app, the window, taskbar and tray icons, the installer and the macOS app icon.
- What Snowy writes after a meeting is called a recap everywhere.
- With the brain icon on, Say Next and Assist draw on your other meetings too, citing each one by title and date.
- A browser sign-in can be cancelled, and the page the browser shows says what is really happening.
- The main window's meeting button reads Open current meeting while one is running.

## 0.1.0-rc18 · 2026-10-15

A ChatGPT or Claude plan can now pay for Snowy's answers with no API key to copy, and live help brings its own expertise.

- Sign in with ChatGPT: a Plus or Pro plan runs answers, suggestions and recaps. Snowy tells you when the plan's limit is reached and stops; nothing is billed elsewhere.
- Use a Claude plan: a Claude Pro or Max plan works through Claude Code, Anthropic's own program, installed and signed in on your computer. Snowy never sees your Claude sign-in, and screen context is off on this connection.
- Cloud AI comes first in setup and Settings › AI, as the recommended choice.
- Live help can add what the model knows, marked as its own ("From experience: …") and kept apart from what was said in the meeting.
- Recaps report where the meeting ended up: a corrected number or a moved deadline shows in its final state.
- Say Next is shorter, and it can recall facts from earlier in the meeting.
- Speed and quality now changes how long the models think, on every provider; Save uses GPT-6 Luna on OpenAI and ChatGPT.
- Fixed: GPT-5.6 and GPT-6 on an OpenAI key work for live help again.
- Fixed: deleting a meeting stops a file import into it, and Reset also forgets the Google Calendar sign-in.

## 0.1.0-rc17 · 2026-10-12

rc17 replaces rc16, which was withdrawn: its Windows build could open with a blank assistant window, and its Mac build quit a second after launch. It carries everything rc16 brought.

- The app starts on every platform, every time, and a window that can't start says so in Snowy's log instead of staying blank.
- Includes all of rc16: the newest AI models, Join & start from the calendar, a cleaner follow-up email, the Back button, the silent meeting audio notice, Parakeet on more computers, and the Mac freeze fixes.
- Install over rc15 or rc16 by hand, or take the update when rc15 offers it; your meetings and settings stay. An installed rc16 isn't offered the update.

## 0.1.0-rc16 · 2026-10-09

The newest AI models, a one-button start from the calendar, and fixes for a Mac window that could freeze.

- Newer AI models: Claude Sonnet 5.5 and Opus 5.5, GPT-6.1 Sol, and the latest Gemini, Grok and DeepSeek. Model settings go back to Automatic once, and later models arrive by themselves.
- Settings › AI › Models has Reset to defaults.
- Join & start: two minutes before a calendar meeting, one button opens the call and starts Snowy with the meeting's title and people. Snowy still never starts on its own.
- The follow-up email reads right: no raw formatting and no transcript references.
- A Back button in the title bar, and the mouse's back button works too.
- A notice when meeting audio stays silent while the microphone hears speech, naming what to check.
- Every computer with 8 GB of memory now gets the more accurate Parakeet speech model.
- Mac: no frozen window from a stuck sound system or a permission prompt, microphones are listed again, and live text keeps up behind the call window.
- Windows: no white rectangle after start-up.

## 0.1.0-rc15 · 2026-10-08

Fixes for the first problems found in rc14, plus a log you can send with a bug report.

- The right speech model: setup now starts in English and names the model each language choice gets. A copy still set to detect the language automatically is asked once to run setup again; your meetings and settings stay.
- Detect automatically now uses Parakeet European, which tells 25 languages apart as people speak.
- When the language changes, the model already on your computer keeps transcribing while the new one downloads.
- Long recaps finish: a reply that is cut off or repeats itself is asked for again, shorter, and Snowy says so plainly if that fails too.
- Mac: with Hide from screen sharing on, the window's outline no longer shows in the shared picture.
- A log for bug reports, kept 15 days. Keep a detailed log adds what Snowy did, never what was said in a meeting.
- This version looks for updates on the public downloads page.

## 0.1.0-rc14 · 2026-10-07

Snowy now knows your Google Calendar, works with the AI of your choice, turns recordings into meetings, and writes recaps that fit the kind of meeting.

- Google Calendar (read-only): see today's and tomorrow's meetings, and from 15 minutes before, Join the call and Start transcribing. The meeting takes the event's title and guests.
- Choose any AI: sign in with OpenRouter, paste a key for OpenAI, Claude, Gemini, Grok, Mistral, Groq or DeepSeek, or run a free model on your own computer through Ollama.
- Until an AI is set up, meetings are still recorded and transcribed, and Summarize now writes the recap later.
- Import a recording (MP3, M4A, WAV, MP4, MOV and more) to transcribe it on your computer and recap it.
- Recaps fit the meeting: General, Sales call, 1:1, Interview, Stand-up or Lecture, plus types of your own.
- Share a recap: copy it, save it as a file, print it or save a PDF, or draft the follow-up email.
- A meeting that ends offline is summarized once the connection is back.
- Hide Snowy from screen sharing with the eye icon (off by default).
- Resize the assistant, and choose a larger text size in Settings.

## 0.1.0-rc13 · 2026-10-01

This release is about the AI during and after a meeting: recaps by topic, questions that see the whole meeting, and a quicker Say Next.

- Summaries become recaps by topic: where each topic stands, decisions with their reasons, blockers and risks, follow-ups with owner and due date, and open questions.
- Questions see the whole meeting (up to about two hours) and understand follow-ups such as "and who is doing that?".
- Say Next and Assist respond to the last 90 seconds, so a suggestion answers what was just asked.
- The first Say Next of a meeting is as quick as the later ones.
- The live transcript breaks into paragraphs instead of one long block.
- A simpler Command Bar; meeting detection always asks before anything starts.
- Settings › AI › Models offers a list of recommended models with plain names and what each is good at.
- Setup offers to open Snowy when you sign in to your computer.
- Install this version by hand: rc12 doesn't offer it as an update.

## 0.1.0-rc12 · 2026-09-30

Better speech recognition, no more echo without headphones, and updates that install themselves.

- English and 24 other European languages use NVIDIA Parakeet on computers that transcribe on the processor; words appear about 1.5 seconds after they are spoken instead of 7 to 20.
- No more echo: without headphones, what the other side said no longer shows up again under "You" (Settings › Audio, on by default).
- The live transcript grows in place instead of retyping itself every second or two.
- Meetings no longer freeze or drift, and a stalled speech recognizer restarts itself.
- Updates download in the background and install when you choose Restart and update, never during a meeting.
- Settings › Audio shows which speech model is in use and why; download, pause, resume or delete models there.
- If your AI provider refuses a model, Snowy moves to the next one and Settings › AI says which.
- Smaller fixes: the Windows installer has the Snowy icon, and no grey squares around the Command Bar on light backgrounds.

## 0.1.0-rc11 · 2026-09-28

rc11 is the first build of the rebuilt Snowy app, and the first that runs on a Mac as well as on Windows.

- A meeting companion with a small dock, a Command Bar, a live transcript, Say Next, Assist, questions with citations, automatic summaries and titles, follow-up email drafts and memory across your meetings.
- Transcription runs on your computer. The speech model (about 630 MB on most computers) is downloaded and checked at first start; English uses NVIDIA Parakeet.
- A Meetings window with search, and each meeting's Summary, Transcript, Recordings and Usage, with export, delete and resume.
- Bring your own AI: OpenRouter (browser sign-in or key) or an OpenAI key.
- Meeting detection for Zoom, Teams, Google Meet and Webex, which always asks and never starts on its own.
- Screen context for typed questions, opt-in per session.
- Settings for audio devices with live level bars, shortcuts, launch at login and running setup again.
- Fixed before release: a freeze a few minutes into a meeting, and transcript text that arrived 7 to 20 seconds late.
- On a Mac, meeting audio needs macOS 14.2 or later. This build has no automatic updates.

## 0.1.0-rc10 · 2026-09-23

The bar becomes the Snowy dot, one AI model runs everything, the cue card can search the web, and local AI models return.

- A small dot floats over your calls: click to start recording, click again to end, right-click for the menu.
- The cue card (the meeting panel) is its own window beside the dot, and can be resized.
- A silent meeting ends itself after 10 minutes by default; choose 5, 20, 30 or never in Settings.
- One AI model for chat, the cue card, notes, titles and the follow-up email, picked from the chip in the chat bar.
- The cue card can search the web through your provider. It is off at the start of each meeting, and sources appear under the answer.
- Local AI models are back, each labelled with the memory it needs and what it gives up.
- New checks: Test microphone, Test system audio and Test transcription.
- Speech setup tells the truth: a missing key or model reads "Needs key" or "Needs download" instead of "Active".
- Fixed: the transcript of a meeting started from the dot is saved every 30 seconds, and a provider's error shows its own message.

## 0.1.0-rc9 · 2026-09-15

The meeting panel answers like an advisor, transcripts get a second careful pass, meeting audio is kept with its note, and updates are found again.

- Asked what to say, the panel gives two or three sentences in your own voice first, then the reasons, each tied to something said in the meeting.
- Setup asks your language first and downloads the right speech models for it; English speakers had been given the multilingual ones.
- After a meeting transcribed on your computer, a slower, more accurate model goes over the whole recording and replaces the live captions (on by default).
- Each meeting's audio is saved as one MP3 with its note, with playback, Download and Show in folder; a switch in Settings turns it off.
- The provider card in Settings is the switch: click one that has a key to use it. OpenRouter is now a provider like the others.
- Chat and write-ups use cloud AI only; speech recognition still runs on your computer.
- Updates find the next release again, and a banner offers Download, then Restart to update. Install rc9 by hand once.
- Fixed: notes on gpt-5.5 no longer fail.

## 0.1.0-rc8 · 2026-09-11

The meeting panel is rebuilt to see every screen and answer in one clear shape, and the app learns to update itself.

- With the eye on, answers can read every display (up to three), and the panel hides itself from that picture.
- One answer shape: a direct line, up to four key facts, and the exact words to say, with a copy button.
- A simpler panel: the ask bar with quick actions, the answer thread, and one toolbar.
- Fast answers give up after 30 seconds and Thinking answers after 90, instead of spinning.
- Cmd/Ctrl+Shift+K shows and hides the bar out of the box, and the bar can be made wider or narrower.
- Automatic updates: Snowy checks at launch and every four hours and installs on your click. Mac builds can check but not install yet.
- Search finds a note from a question in plain words, and untitled meetings are named by date and time.
- macOS: the Globe key shows the bar only on a tap, so Fn shortcuts work again.
- Fixed: notes failing on GPT-5.6, and light text on the light theme.

## 0.1.0-rc7 · 2026-09-02

Answers come at two speeds, the bar and meeting panel turn to dark glass, and setup comes down to a single API key.

- Entering a provider key sets up every feature with a suitable model; a choice you made yourself is kept.
- A model chip where each model is used (chat, the meeting panel, the follow-up email) replaces the model settings pages.
- The meeting panel has a Fast or Thinking switch, and Think deeper refines a fast answer.
- Answers appear as formatted cards and stay as a thread you can scroll back through.
- An eye toggle lets a question look at your screen too (off by default).
- Resume meeting records another session into the same note, with one write-up.
- Ask the chat to change a shortcut or open a Settings page, and it does.
- Shortcuts are one list: click one and press the new keys. Setup lets you pick a text size.
- Fixed: Back to notes works at larger text sizes.

## 0.1.0-rc6 · 2026-09-01

The assistant bar becomes the front door: daily use starts and ends at the small bar on top of your screen.

- After setup, the bar appears at every launch, one click from recording. The main window opens when you ask for it, or when a meeting ends with a write-up to read.
- Clicking the tray icon shows the bar.
- The bar is visible in screen shares by default; a new Hide from screen sharing switch hides the bar and the meeting panel.
- While a meeting records, the bar turns into the meeting panel in place.
- Listen is now called Start meeting.
- A warning icon on the bar lists what's left to set up, and speech model downloads show their progress there.
- Settings has a cleaner look, and Replay onboarding runs setup again while your notes, keys and history stay.

## 0.1.0-rc5 · 2026-08-31

A big simplification: Snowy is rebuilt around one loop, start a meeting and get the write-up.

- Setup asks one plain question (private on this computer, or an online service) and downloads the right speech model for you, without making you wait.
- The assistant shortcut opens a compact bar: type a question, or press Listen to start a meeting.
- A redesigned live meeting panel with quick actions: What should I say?, Recap so far and What's still open?
- The transcript is hidden by default during a meeting; one click shows the last few lines.
- Home is your meeting history by day, with search in the window header.
- A meeting opens on its Summary, with a new Follow-up email button that drafts the email for you to edit and send yourself. Snowy never sends anything.
- Removed: creating notes by hand (notes you already typed still open), write-up templates, and the extra default folders.
- Calendar sync and audio-file upload are hidden for now.

## 0.1.0-rc4 · 2026-08-26

Snowy learns that meetings repeat: a recurring meeting starts already briefed on last time, and long meetings hold up better.

- A recurring meeting shows when it last met and how many items are still open, with a one-click What's still open?
- The assistant is briefed before anyone speaks with the last meeting's decisions and commitments, and where they stand now.
- Write-up templates: 1:1, Standup, Sales call, Interview, Planning or standard notes, remembered for the next meeting of the same series.
- Copy recap for sharing pastes cleanly into Slack or an email.
- Note search finds meaning, not just matching words, and shows the passage that matched.
- The meeting assistant gets ready as the meeting starts, not at the first question.
- Meeting audio that stops mid-meeting (often after the laptop sleeps) restarts itself; if it can't, the panel says "Microphone only".
- Fixed on Windows: a damaged download no longer looks like a success.

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
