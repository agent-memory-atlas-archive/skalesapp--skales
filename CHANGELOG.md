# **Changelog**

All notable changes to Skales will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),

and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## v12.9.45 - Steer

**A release you can steer: the chat drives Skales Code, a line typed mid-turn joins the work, Stop acts at once, and you can see Skales working on your screen.**

Skales Code became something a developer can lean on. Stop acts at once and the window stays fast in long sessions, answers arrive whole, a message typed during a run waits visibly and can be edited, sent now or discarded, and a command can be refused with a reason the model follows. Esc, Shift+Tab and the slash commands you know from other coding agents are there, the status bar shows model, context and cost, and the chat itself can start, feed and read a Code session on any folder, from the computer and from the phone.

Skales also learns the way you work: episodes and facts every hour, a quiet review that writes down what worked as procedures, and /learn, /refine and /btw to steer it. When it controls the screen you see it, with a frame in your accent colour and the comet on every click. Flow no longer carries your memory into fictional work unless you ask it to, picks its own design direction, and learns from your thumbs. Settings open on General and read more calmly, Iris is the one voice door, and large attachments arrive whole on every surface.

Skales now brings craft with it: reviewed skill packs for motion, short-form video, frontend design, Office documents, print and brand work and persistent research load by themselves where they help, letters come out on your letter paper, a project becomes a launch video with /launch, and Godot games are built, run and recorded from Code. Every plugin page offers three modes, from doing it yourself to letting the AI do it with each release step waiting for your click, even across a restart. Long runs show every step with its cost, and a run that cannot work says so before it spends anything.

### Added

- **Create editable business letters with your logo, running headers and footers, address window, references, fold and hole marks and page numbers.** The logo and the marks show in Word and LibreOffice alike, the logo keeps its proportions, and a document that asks only for a header or page numbers keeps its page as it was.
- **A launch video of your project, straight from Skales Code.** Type /launch, optionally with a tone like polished or cinematic or a format like vertical for reels, and Flow makes a short launch video from the project's own name, words, colours, fonts, screens and logo, renders it once it is ready and writes a post text beside it. Environment files, keys and secret folders are never read. The same works in words from any chat, and Flow has a new Launch video template.
- **Direct motion films with a clearer beat plan and visual review.** Flow motion now brings guidance for using real references, seekable movement, restrained sound and a check of the key frames before the full film is rendered.

- **Godot games get built, run and shown.** Skales finds Godot on your computer, imports and checks the project, plays it for a few seconds, runs its tests, records a short clip as proof and exports builds. An engine that hangs is stopped and named instead of waiting forever, and a game with a script error is not reported as working. Without Godot installed, Skales says where to get it. A new game-development skill routes Godot, Unity, Unreal, Bevy, Phaser, PixiJS, three.js, LOVE and pygame work to the right guidance.

- **Thumbs up and down on every Flow result.** Up keeps what worked - the direction, the structure, the pacing, the type - as a short lesson, down keeps what to avoid, with one optional line on why. The lessons sit in one skill on the Skills page, marked Flow only, with Undo for the last change, and only Flow reads them. A Flow conversation you do not rate teaches nothing.

- **"My memory" in Flow, per project.** A chip in the Flow composer and in the workspace head decides whether a project may use what Skales knows about you. Switched on, Flow gets your name, your brand and the style facts you saved, and nothing else. Every new project starts with it off, and the choice survives a reload.

- **A message you send while Skales works reaches it at the next step.** Type while a turn is running and your message joins that turn after the tool call in flight returns, instead of waiting for the whole answer; several messages in a row arrive as one, pictures ride along. Prefer it to wait? Choose "After the turn" in the strip above the composer or in Settings, and it runs as its own turn once the current one is done. The strip shows each line as waiting and then delivered, lets you edit or remove it, and keeps it through a reload or a restart. The chat, Iris, the Buddy and the phone all use the same queue.

- **Skales learns while you work.** Every ten messages or ten tool steps, a short look back on the helper model keeps facts about you, how-to lessons and corrections of how you want things done, and one quiet "Memory updated" line in the chat links to what it kept. Never in Incognito, and its cost is part of the conversation's price. Switch it off in Settings, Memory, Learning.

- **Procedures Skales writes for itself.** When a repeatable way of doing a task comes up, Skales writes it down as a skill with steps, pitfalls and a check, and improves it next time instead of starting over. It only changes a skill after reading it, never touches a skill you brought unless you ask, and the Custom Skills page shows these as "written by Skales" with their version, how often they were read and an Undo for the last change.

- **/learn, /refine and /btw.** /learn followed by a folder, a link, a PDF or nothing ("what we just did") turns it into a procedure. /refine runs the look back now. /btw asks a side question and answers it without interrupting a turn that is running. All three work in the chat, the Code window, Telegram and from the phone.

- **Conversations are summarised during the day.** Finished conversations get their summary and facts hourly, at most 24 a day, for every installation, whether or not Dreaming is on, so "what did we do this morning" has an answer at lunch.

- **Plugins speak your language.** A plugin page follows the language Skales is set to - not the language of your computer - and switches along while it is open. A plugin can carry its own translations, and its name and description in the menus follow them. E-Learning now speaks all twelve languages, starts a new course in your language (a course you already have keeps its own) and brings an English example course next to the German one.

- **Design templates for E-Learning, and a look you can change in words.** Six complete looks - Warm, Corporate light, Corporate dark, Playful, Editorial and Technical - set colours, fonts, spacing, corners, shadows and a dark scheme in one click, with text that stays readable. Or say what you want ("more playful", "dark", "corporate in our brand kit"): the new look is proposed first and applied with a click, undo takes it back and every earlier look stays in a list to restore. Your Brand Kit and the design style packs from Flow are used when you ask for them, and the chat and the plugin's assistant can make the same change. Courses keep passing the LMS check with every look.

- **A plugin you switch on appears in the sidebar.** It is pinned once when you switch it on; if you unpin it, it stays unpinned, and switching it off takes it out again.

- **Skill packs that bring craft to Flow and the chat.** Motion design, cutting your own footage into short-form video, frontend design, print and brand work, Office documents (designed PowerPoints and letters on your letter paper) and persistent research arrive as skills that load by themselves in the Flow mode or the conversation where they help. Skills built from open-source projects are rewritten in Skales' own words, name their sources on the skill card and in the notices, and ship only after a person has reviewed the rewrite.

- **Collages in Flow.** A new Collage template in image mode composes your pictures, plus generated or found ones where the brief asks for more, into one image in the format you chose, and saves it as a picture when the turn ends. Save as image stays available to save it again after a change.
- **Business plugins get new versions without a new Skales release.** A plugin Skales makes for your business, like E-Learning, shows its next version on the Plugins page when your Skales account includes it. You read what changes before you confirm, your courses and files stay as they are, and without the licence the plugin keeps working and the page tells you why there is no update.

- **Flow edits your footage.** Attach a phone video, a recording or a long take to a Flow project, in any mode, Auto and Free included, and tell it what film you want: a short with a hook in the first two seconds, a long-form cut with the silences tightened, a UGC clip, a highlight reel. Flow sights the recording (shots, pauses, what is said with timings), looks at the moments that matter, writes the cut, crops it to 9:16 or keeps it 16:9, lays music under it that ducks when someone speaks, adds narration, burns in captions that follow the cut, inserts other clips where they belong, and draws motion graphics over the picture: titles, lower thirds and callouts rendered frame by frame with a transparent background and laid over the footage. The finished MP4 lands in the project. A recording of any ordinary length now arrives: attachments used to stop at 15 MB and anything larger was left behind without a word.

- **Say which service, and Flow and the chat use it.** "Make it with Kling", "use OpenRouter", "Sora 2 Pro", "in 9:16 and 4K" in a message now decides the service and format for that turn, over the composer's preselection; when nothing is said, the composer applies, then the models you chose per task under Providers > OpenRouter. Every video service Studio knows is reachable from the chat and from Flow: OpenRouter (Veo 3.1, Kling 3, Seedance 2.5, Sora 2, Runway Gen-4.5, Wan, Hailuo, Grok), Google Veo, Kling, Runway, Seedance, MiniMax, fal.ai LTX, Atlas Cloud and Skales IQ. A service you name without a key of its own runs through OpenRouter when OpenRouter carries it, and the reply says so. A length, ratio or resolution a model cannot make is fitted to the nearest one it can, and the reply names the change instead of calling the clip what you asked for. The finished clip goes straight into the Flow project.

- **Hundreds of specialists on call.** Ask for a specialist in any chat, a Unity architect, a PPC strategist, a penetration tester, and Skales finds one in its bundled agent library, reads its working method for your task, or hands the task to a sub-agent that works as that specialist and brings the answer back. Handing over asks first and shows its card like any sub-agent. The library is searched when needed, it is never pasted into every message.

- **Music and sound effects on request.** The agent makes a music bed or a sound effect with the service you choose: OpenRouter (Lyria 3, and the music model you picked for OpenRouter is the default), ElevenLabs music and sound effects, Hugging Face (MusicGen, Stable Audio) or Skales IQ.

- **What you send while Skales Code works waits where you can see it.** A message sent during a run appears at once above the box you type into, greyed as waiting, and says whether it joins at the next step or after the turn. You can edit it, take it back, hold it for after the turn or send it now; when the run reads it, it is marked delivered and the log shows at which step it arrived. Your phone sees and changes the same list.

- **"No, and instead" on a permission card.** Under the refusal, write what Skales should do instead: the step is declined with your sentence as its answer and the run carries on in that direction. A plain No still ends the run. It works the same from the chat and from the phone.

- **A run that repeats itself stops and asks.** When the same tool is called three times with exactly the same input, the run pauses and asks whether to keep going, try it differently (and how), or stop.

- **Shortening shows its numbers.** Every time a long session is summarised to fit the model, the log shows it as its own item with the context before and after in tokens, and /compact while a run is working is taken at the next step instead of being refused.

- **Settings works on a phone and in a narrow window.** When Skales is opened in a phone browser or a small window, the search and the categories move to the top, the categories scroll sideways, and a setting's control moves under its name instead of squeezing it to a letter.

- **You see Skales working on your computer.** While it clicks, types or navigates for you, in the browser or on the desktop, a glow in your accent colour runs around every screen, a comet flies to the point it is about to click and a click lands as a pulse. A small bar at the top says what it is doing right now and has a Stop that ends the run like Stop in the chat. Your apps, Buddy and AIPointer stay clickable underneath, and the glow goes away when the run ends, crashes or stops moving.

- **Passwords and payment details stay yours.** When the next field is a password or a card in a window you can see, Skales stops and hands you the screen; you type it yourself and press Continue. It never types into such a field.

- **Route each turn, off by default.** Under Assistant > Writing help > Decisions, Jev can now pick which of your configured models answers each turn (your chat model, planning and executing models, and fallback chain) by what each can do and what it costs, and pick which fallback takes over when a model fails. The same slot also takes OpenRouter's Auto Router, limited to your own OpenRouter models. Every switch shows as one quiet line in the chat, and its price counts in the turn's cost. The card says what one pick costs and how long it takes before you switch it on.

- **The pick is ready before you send.** With routing on, Jev reads your draft once you pause (from about 40 characters) and the composer shows its choice, for example "→ deepseek-v4 · Code", in the chat, Skales Code, Flow and Buddy. Change it with a click and your choice wins; when you send, the pick is used at once if the text is still essentially the same. Never in an incognito chat, and the small questions count in the turn's cost.

- **Flow's Auto picks with Jev.** With Jev in the Decisions slot, Flow's Auto asks it which kind of thing to make and which template fits, from your brief and your attachments, in a fraction of a second; the helper model still writes the scoping questions and still decides whenever Jev cannot. With routing on, Flow turns go through the same model router as the chat until you switch the session's model yourself.

- **Skales Code answers the keys a developer reaches for.** Esc stops a running turn through the same stop as the button, pressing Esc twice opens your last message for editing, and Shift+Tab in the composer steps through Ask, Plan, Code and Auto. All three are listed with the other keyboard shortcuts. An open menu, dialog or editor, and the terminal, keep their own Esc.

- **Six slash commands every coding tool has.** In Skales Code, /undo takes back the last turn that changed files and puts your question back in the composer, and pressed again it takes back the turn before. /resume carries on a session that stopped half way, or opens your sessions when nothing stopped. /cost shows what the session has cost and what fills its context, /diff opens the review of what changed, /init writes or updates the project instructions from the project itself and folds in the rules other coding tools left there, and /model opens the model picker or switches straight to the model you name.

- **The Skales Code status bar shows the model, its thinking effort, how full the context is and what the session has cost.** The cost is the same figure the chat shows for a conversation.

- **Skales Code streams as it works, however long the session.** The answer, each tool call and its result, the queue, the permission card and the run's progress now reach the Code window the moment they happen, and only what changed travels: a session with hundreds of messages streams as smoothly as a new one, and an answer longer than twenty thousand characters arrives whole instead of losing its beginning while it streams. A run started from the phone, or the next message waiting in the queue, appears without a refresh. After a reload the window picks the answer up exactly where it stands.

- **The chat hands coding work to Skales Code.** Ask in any chat, on the computer or in the phone's Remote chat, for a job in a project folder: Skales asks once, opens a coding session on that folder with the task, and the Code window opens on it while your chat stays where it is. The same chat can send the session a follow-up (a working session keeps it in its queue and reads it at its next step; a session you let run on Auto takes it without asking again), tell you where it stands, and read back its last answer and the files it changed. When the session stops to ask for permission, you answer in the Code window, and the chat links you straight to it. A link to a coding session in an answer opens the Code window on that session.

- **The phone reaches more of the computer.** A large file from the paired phone goes straight to the computer over the network when remote access is on and the phone can reach it; otherwise the relay carries it, at any size, paced to what the computer has written. A Code session opened on the phone shows its waiting messages, its model, effort, context use and cost, the learning and side-answer lines, and the router's pick, and the phone's composer can ask the computer's router while you type.

- **A line you sent from the phone that a stopped turn never read can be sent or discarded there.** The phone shows it as not delivered with Send now and Discard, and both run on the computer exactly as the chat window's buttons do: Send now starts the turn over the conversation as it stands, without writing the line twice. Reopening a conversation on the phone also brings the computer's whole spend for it, rolled-back turns and background costs included, marks a finished Skales Code run as a quiet line, and each answer carries what the turn's own helpers cost on top. The phone's composer can show which model the router would pick while you type, with your configured models to choose from, when routing is on.

- **Give a plugin a job, and it does the whole job.** "Give a job" on a plugin starts from examples and lets you pick what it should work on. The plugin's assistant then presses the same buttons you have on the page, one step after the other, and every step shows up there and can be undone. Tell E-Learning what course you need and it creates the course, fills in the briefing, sets the look, writes the slides with their narration and voices them; when it is done, you look it over and release it with one click.

- **Prepared, not sent: approvals that wait for you.** Whatever a plugin's assistant, a scheduled plugin run or a webhook would send, publish or finish now waits as a card - on the plugin, on the board in the cockpit and on your phone. The card is still there after a restart or days later, pressing it twice still does it once, and declining it ends the run and says so. Pressing it costs only what that one step costs.

- **Plugins can sign in to your services.** A plugin that works with a CRM, a shop or a mail service connects with your own sign-in in the browser. What the service hands back is kept encrypted on this computer and never reaches the plugin's page.

- **Webhooks for plugins.** A service you use can start a plugin's assistant with a signed call - a new order, a new sign-up. The plugin prepares what follows and waits for your click before anything goes out.

- **Your plugin data, to take along or to delete.** Next to each plugin in Plugins you see what it has collected on this computer, save a copy of it as one file, or delete it while the plugin stays installed. Keys and sign-ins are never part of the copy.

- **A plugin made for a newer Skales says so.** Instead of opening halfway and failing, it names the Skales version it needs.

- **Three ways to work with every plugin that has a page.** Under the page you choose Manual, With AI or AI does it, and the plugin remembers your choice. Manual hides the plugin's AI buttons, With AI keeps them and adds a line to ask the plugin for anything else, and AI does it takes a whole job, with example jobs to start from: the AI does the work, you approve what it prepared, and every step stays correctable on its own. E-Learning is the first plugin with all three.

- **See every step of a run and what it cost.** In Flow, the price in the head opens the steps of the conversation: grouped by the message that started them, each with its tools, whether it worked, how long it took and what it cost, with waiting approvals and team members in the same list; the chat's full report shows the same steps. The steps add up to the price in the head and to the price the phone shows, and a reload in the middle of a run shows the same steps again.

- **A Flow start checks what it needs before anything is paid for.** When a planned step is missing its tool, its key or the local renderer - a clip without a video service, music without a music service, a cut without FFmpeg - Flow says which step needs what, links to the place in Settings where it is set up and names the way around it, such as OpenRouter, before a model is asked. Every video service you have set up counts, OpenRouter included. Nothing is charged for a start that cannot run.

- **Golden runs.** A run that came out right can be kept as a reference and replayed later on the current version, and the comparison says what changed in the work rather than in the wording: a tool that is missing or now fails, a file that no longer appears or has another type, a bill or a duration well above the reference, or an answer that ends on a promise.

### Fixed

- **Flow keeps the conversation clear when it looks at pictures.** Pictures opened during a run no longer appear as extra messages from you, and a message you sent with a picture still shows your own words. Results and their ratings stay with the right turn after you reopen the project.

- **Keys that cannot be opened on this computer are kept instead of erased.** After a backup was restored on another computer, or the key file was lost, saving a setting no longer deletes the stored key. Editing a provider's model keeps that provider configuration too. The provider card says which key to enter again before connecting.

- **Normal chat and the first Skales Code turn leave more room for your work.** The instructions sent with every message are shorter, and the rules that shape what Skales does stay in them: it checks before it says something runs, exists or is connected, reads a file you ask about instead of saying it cannot, keeps its working files out of your repository, works through its plan instead of rewriting it, and sends small helper errands to a cheaper model. Attached images still reach it through vision, and Skales Code still shows its steps, file links and Keep or Revert on every edit.

- **The chat's full report counts what an undo or an edit removed, like the price under the composer.** Money already spent stays in the total, so Analyze and the composer always show the same figure.

- **Team runs now count in the conversation's price.** The members of a team run and the coordinator's brief and verdict were paid calls that never reached the price under the composer, the phone's figure or the conversation's spending limit.
- **Code Auto keeps working through a long series of quiet steps, and still stops a run that goes in circles.** A change that stays made counts as progress, such as adding line after line to one file, a series of quick edits to one file, or editing one file after another. Rewriting the same file over and over, sending the same person or address message after message without having learned anything new in between, or undoing the previous change is recognised as circling, and so is starting one background command after another without reading what they do.

- **Bundled agents keep their identity when edited.** Their cards still allow edits and copies; Reset restores a changed built-in agent instead of presenting it as a deletable custom agent, and it appears for every changed built-in, including ones changed in an earlier version.
- **Local voice setup installs through your package manager.** The guide for local voice engines uses pipx or winget instead of running a downloaded installer.

- **Settings search uses the full results area.** No blank strip is left below the results, and the task time limit names its default under its scale, readable in every language.

- **Still emojis stay still in large chat messages.** Only emojis that really have an animation move, and none is left waiting for an animation that does not exist.

- **Code `/undo` restores files changed by shell commands.** Each command is recorded before and after it runs, and a command left running in the background is sealed when it exits. Undo checks for later edits before restoring a whole turn, including turns that mix shell and file tools; ignored files and files holding keys, tokens or passwords stay outside the record. A command always runs: on a computer without Git, or in a folder too large to record, the Code window says why shell Undo is off there, and a command cut short by a restart never blocks Undo for the turns before it.

- **Code backups live in Skales' own data, outside your project.** Backups left in the project move there on first use, and making a backup no longer edits the project's `.gitignore`. In a read-only project the old backups stay where they are and Undo keeps working.

- **Flow keeps working after a German next-step announcement.** When Skales says "Ich prüfe jetzt …" in Chat or Flow, it takes that step in the same run. Repeated announcements end with a named no-progress message instead of appearing as a finished result.

- **Long conversations save without slowing down as they grow.** Changes made to a conversation from outside are still picked up.

- **A follow-up chat turn checks pictures already in the conversation.** If the selected model cannot read them, the usual question about reading pictures appears before the turn starts.

- **GLM-5.3 text models route pictures through the Vision Provider or show the blind-model question.** GLM-5.3-Flash, FlashX and Flash Preview and the GLM V models, such as GLM-4.5V and GLM-4.6V-Flash, keep their native image input, through Ollama too.

- **A Code picture described by the Vision Provider is read once.** The image stays visible in the transcript without being sent to the provider again on the next step.

- **Continuing with one agent of a team hands its answer to your next message, in the chat and in Skales Code alike.** The answer shows as one folded line, the model reads it together with what you type next, and the conversation's title and the task Skales keeps in mind come from your own words, never from the agent's answer.

- **Unrestricted Auto runs move past a repeated tool call without waiting for a person.** A supervised run still shows the three-choice loop card.

- **The chat reopens only a chat conversation after a restart.** Code work no longer opens in the chat window.

- **"Send now" in the chat delivers the selected unread line exactly once.** After Stop, each waiting line can be sent on its own, the same way as from the phone, and a start that fails says so on screen.

- **Flow planning and chat titles count toward the conversation's cost, without appearing as lines in the conversation.** What Flow asks and decides before a project starts is paid for once, by the project that uses it, and the planning of a project that was never started stays visible on Flow's home page. Naming a conversation adds its price to the total, even when the proposed title is not used, and no longer moves the conversation to the top of History.

- **Helper calls through OpenRouter show what they actually cost.** Flow's planning, the other small helper calls and reading a page in the browser carry the price OpenRouter reports into the conversation's total. A call reported as free stays free, and a call without a reported price stays marked as unpriced.

- **Large files from the phone stream to the desktop.** Video, documents and course packages from the paired phone travel over the relay at any size and are written to the workspace as they arrive. The desktop confirms what it has written, so the phone never sends faster than the desktop takes it and its progress bar shows what has actually arrived. The desktop checks for room before the first byte and a refusal says how much space is free; a transfer cancelled on the phone is removed at once; a very large document stays in the workspace for Skales to read in parts instead of being loaded whole. Completed uploads survive a desktop restart until the same phone uses them in a chat turn; partial files left by a restart are cleaned up. Incognito keeps its named in-memory limits.

- **An oversized Incognito attachment names the size limit.** It no longer ends in a generic server error.

- **Long audio files can be transcribed.** A recording longer than one request to the speech service is cut into timed parts and put back together with its timestamps, including phone recordings in M4A and MP4 that could not be read before. Audio files attached in the chat, on the new-chat page and in Skales Code travel to this computer in pieces, so their size no longer matters, and a full disk or an upload that broke off is named on screen.

- **Course playback controls now follow the course language in all twelve supported languages.** Navigation, task hints, help, and completion messages no longer fall back to English for other course languages.

- **Voice notes and private text files are no longer rejected by hidden size ceilings.** Existing file and transcription tools can read or save what was accepted at upload, and a recording too large to send in one message says so, with the way that works.

- **Cloud video generation has a Stop button in Studio.** It sits with the running cloud video, stops that job at the provider where the provider allows it, and names any job that may keep running or charging; the next video starts with a fresh Stop.

- **The Studio video editor sees media uploaded through Chat and Flow.** Those video and audio files now appear beside gallery media.

- **Studio finds every unfinished editor job after a reload.** The making list and failed video recovery show every job that is still running or waiting for you, and stay quick however many exports you have made.

- **The computer control comet stays on its target when the app is zoomed.** Changing the app's text size no longer moves the pointer cue.

- **Computer Use can drag between two points from the same screenshot.** The new action holds the mouse button through the movement and reports a platform error on failure.

- **Flow keeps every file selected for a new project.** Additional attachments no longer disappear when many files are chosen at once.

- **Code search now finds text in UTF-16 files, including PowerShell output.** The file list and search agree on those files, and ordinary words containing "dd" no longer trigger the raw-disk command warning.

- **A video job that fails on a broken file says so and lets you act.** A video cut off during an upload used to sit under "Continue where you left off" as "waiting for you" for ever. The sighting now checks the file first and fails at once as "Failed: file incomplete or damaged", with the reason, and offers Upload the file again and Discard, on the Flow entrance and in the video editor. "Continue" lists only work that can go on; a job that stopped when Skales did no longer spins as running, and jobs already stuck this way are shown as failed without anything in your data being rewritten.

- **Flow no longer carries your memory into a design.** A Flow project got your name, your memory index and your standing instructions on every turn, and they turned up in the pictures and the project notes. Flow now works from the brief and the project files unless you switch on My memory, and a Flow conversation no longer writes into your memory or is read into it later.

- **A Flow answer that still ends early says so.** When an answer reaches the model's output limit even after Skales asked for the rest, Flow shows the note under it, and lines that arrive after the run ended appear without reopening the project.

- **A spoken line during a running turn is answered.** Speaking to Iris while the same conversation was working wrote the line into the transcript and nobody ever answered it; it now joins the running turn like a typed one.

- **A scheduled job that keeps failing says so in the chat.** After three failures in a row a job is paused as before, but now the chat you have open gets one line with the last error and where to fix, switch back on or delete it, and the notification actually arrives; before, the pause happened in silence.

- **Settings opens on General again.** Opening Settings from the gear, the tray or the /settings command no longer lands on the page you left last time, such as Plugins. A link to a particular setting still goes straight there, and a reload while Settings is open comes back to where you were.

- **The Settings search has one clear button.** A second one drawn by the browser stood next to it.

- **With a decision model on, browsing asks it on every click.** The chat model clicks by reference, which used to bypass the decision model on every click that was not binding; now each click is checked against what the element is called, and what the decision model read comes back with the step.

- **Install Chromium works without Node.js, shows its progress and can be cancelled.** The browser download that ships with Skales could not start in an installed app, so every press fell back to npm: on a computer without Node.js it failed with an npm message, and on one with Node.js it ran npm inside the Skales program folder, which removed files the app needs to start. The built-in download now runs on its own, the button shows which part is loading with megabytes and a percentage, Cancel stops it and everything it started, and a failure shows the download's own reason. npm is only tried when the built-in download is missing from the install and npm is actually there, and then in a folder of its own inside your Skales data, never in the program folder. No install process keeps running after Skales is closed.

- **"With GPT Image" works without an OpenAI API key.** Asking for GPT Image or DALL-E with only a ChatGPT sign-in failed with "OpenAI API key required", because the sign-in does not include OpenAI's image service. With an OpenRouter key the picture is now made with GPT Image through OpenRouter, the same way videos already were, and the reply says so; DALL-E, which OpenRouter does not carry, becomes GPT Image 2.5 Flare and the reply names the change. Without either key the reply says which key to add. GPT Image 2.5 Flare and Sunburst are in the model lists.

- **Stop ends a video job that is still being made.** When a video was being generated at a service, Stop ended the chat turn but Skales kept waiting for the clip for minutes. Stop now ends the wait at once, in the chat and in Flow. Where the service can cancel a job (Replicate, Runway, fal.ai) the job is cancelled there too; where it cannot (Google Veo, Kling, OpenRouter, Atlas Cloud, Skales IQ), the reply says that the job keeps running at the service, may still be charged, and will not be collected.

- **Share a window says why when there is nothing to pick.** In the Buddy a click on the window button could do nothing at all when the system returned no window or the question failed, which happened on Windows. The Buddy and the chat now say "No windows found" with the reason: what the system reported, that Skales is the only open window, or, on a Mac, that the Screen Recording permission is missing.

- **A damaged installation says so before it starts.** Skales now checks at every start, before its server runs, that the files it needs are in its program folder. When some are missing, a screen says the installation is damaged, names what is missing, and its download button fetches the installer for your system from the current release, with your data untouched; a server that fails to start because a part of the program is missing shows the same screen instead of a short error and a quit. Files that differ from the ones that shipped are listed in Diagnostics and do not stop the start.

- **Diagnostics show why the server failed and which parts of Skales are not running.** A crash now shows the line that names the error, not only the last lines, which were usually a list of file paths. A background job that could not load a part of the program used to log it as non-fatal and carry on silently; each one is now listed under the installation, with the job it stopped and how often.

- **The Mac updater no longer damages a downloaded disk image.** When Skales was started again while the update's disk image was open in Finder, it downloaded the same update a second time into the open file, and copying Skales out of it then failed. A download now goes into a file of its own and takes the installer's name only after it verified; a version that is already downloaded and verified is not fetched again; an open disk image is never written. When the installer was already opened and the old version is started again, it says the update is waiting: move Skales into Applications, or open the installer again from there.

- **Windows updates no longer start over a running Skales.** When a Skales process of the installation outlived the shutdown before an update, the installer used to start after ten seconds anyway and replaced files under a program that was still running, which could leave the installation broken. Skales now ends those processes itself, and when one cannot be ended it does not start the installer: it stays open, names the process, and says how to end it.

- **An update is announced once.** A new version showed up as a banner on the dashboard, a notice, a dialog and the update chip at the same time. The chip in the corner and the dialog once the update is downloaded remain; the chip also says when a version comes with new licence terms.

- **Large attachments arrive whole.** A phone video, a recording or a big archive attached in Flow, the chat or the Code window could arrive cut off and be kept like that, so a video would not open. Files now travel straight to disk at any size, from the desktop window and from the web UI alike; one that arrives incomplete is refused with how much came instead of being kept half, and the disk is checked for room first. When Flow finds a recording it cannot open, it says so and asks for it again instead of building the film from generated stand-in footage.

- **The preview's own window no longer hides the course title under the window buttons,** and closing it no longer leaves a row of "That preview is not open any more" errors: the preview comes back into the page, it stays inside its slot instead of covering the page's toolbar or a message above it, and the same error no longer stacks.

- **Flow asks its questions once.** Answering the questions before a build is recorded first, so a reload, a second window or a second click can never start the build twice; your answers stay readable in the conversation, and long questions wrap instead of pushing the card apart.

- **Flow starts on Auto.** The start page no longer preselects Prototype, so an attachment no longer ends up in a prototype: Auto picks the kind of result from what you write and attach - a recording always leads to video - and a mode or template you pick yourself stays picked.

- **Skales Code wears your accent colour the moment you pick it.** An accent chosen in Settings while the Code window was open only arrived after the theme itself changed. It now follows at once, after a restart and in every theme that takes an accent.

- **Carrying on a conversation with a picture in it asks first when the model cannot read pictures.** The question the first picture gets, switch to a model that reads pictures or continue with a description, now also comes when you continue a Skales Code session or a phone conversation whose history holds a picture, instead of the turn failing on the picture.

- **A picture is described once.** When your model cannot read pictures and the Vision Provider describes them, each picture is described once instead of again at every step of every turn, so a long run no longer pays for the same description over and over.

- **Long Skales Code sessions stay fast.** While an answer streams in, only that answer is redrawn, not every turn above it, and turns far above the screen are drawn only when you scroll to them.

- **The Skales Code file column shows everything the session touched.** Files it created, changed and deleted are marked A, M and D, also in folders git ignores and in folders that are no repository, a folder holding a change is marked too, and the column opens on Changes whenever there are any. Dependency and build folders are left out.

- **Stop in Skales Code acts at once.** Pressing Stop while an answer was streaming could wait seconds behind the window's own background reads before it even arrived. Stop now travels on its own, the window says "Stopping" immediately, and it only shows the session as stopped once nothing of it is still running; if a step is still finishing, the window says so instead of pretending it has stopped.

- **Skales Code opens faster.** The review column, the preview, the browser, history and the command palette load when you first need them, fetched quietly in the background, and the clock that counts a run's minutes no longer redraws the whole window every second.

- **Patches apply without Git.** The patch tool needed Git installed and failed on a Windows machine without it. It now applies patches on its own, in the usual diff format and in the block format several models write, finds each change even when the line numbers are off, and keeps Windows line endings and UTF-16 files as they were. Git is only needed for a patch that carries binary content, and the message says so.

- **Edits land in Windows files.** A change to a file with Windows line endings was reported as "not found" whenever it spanned more than one line. Edits now match regardless of line endings, keep each line's own ending, and also find a block that differs only in tabs against spaces or in a character or two. A file with a byte-order mark or in UTF-16 keeps its encoding.

- **Files written by PowerShell are read as text.** Output that Windows PowerShell 5 redirected into a file was refused as a binary file. Those files are now read as the text they are, and the answer names their encoding.

- **Sub-agents no longer stop on an empty Skales Local.** A sub-agent meant to run on a model on this computer went to Skales Local even when no model was chosen there, and stopped on "no model is chosen". It now only goes to a local runtime that has a model ready, and otherwise runs on the model the conversation uses, with a note saying why.

- **Paths with spaces in scripts are named.** When a script hands a folder like "Star Wars Endspiel" to a program without quotes, the result now says which line split the path, instead of leaving only the program's "invalid path" to go on. PowerShell scripts are written so that a folder with an umlaut in its name reaches the program intact.

- **No more warning noise for the search tools.** The log no longer warns on every call to the file search tools, and every tool the assistant can call has its permission level set.

- **Videos through OpenRouter finish.** A clip made through OpenRouter was asked for with the prompt alone, so the ratio and length were lost, and the finished file was never collected, so the wait ran out after ten minutes. Ratio, length, resolution and sound now go with the request, fitted to what the model accepts, and the file is fetched when the job is done.

- **Burned-in captions have a readable size.** Captions came out about four times too large, a caption line could fill a third of the picture. They are now sized to the frame, and in a vertical video they are bold and sit above the buttons of the apps the video will be watched in.

- **The server stays up when a page gives up on a request.** When a window closed a connection while sending, the server could end with "aborted" and restart, taking every open answer and background job with it; four times in twenty seconds on one machine. That case is now recorded and survived.

- **A new Flow session starts without a brand kit.** The first saved kit used to be switched on for every new session; now a kit is used when you pick it.

- **Studio and Flow render films again that stood still but were refused as "not reproducible".** Before a render starts, Skales visits some frames twice and compares the two pictures, to catch a composition whose picture depends on the frame shown before instead of on the frame number. That check only looked at pixels, and Chrome sometimes draws an unmoved image a little differently the second time, because it scaled it along another path on the way there: a logo that stood exactly where it belonged came back up to 12 shades apart over a few hundred pixels, and the whole film was refused. The check now also asks the page what it shows, where every visible element stands, its size, transform, opacity, filters, text and canvas content, on both visits. If the page stood still, a small difference in the picture is the browser drawing, and the render goes ahead. If an element moved, the render stops as before, and the message now names that element and what changed, so you know what to fix in the composition. Elements a composition only keeps for measuring, which are never drawn, do not count.

- **The last answer of a long run arrives whole.** A long answer is shown from its first word while it is written, instead of starting somewhere in the middle, and an answer the model cuts off at its output limit is asked for the rest until it is complete; if it still ends at the limit, a line under it says so. The price of every part lands on the one answer.

- **A stop no longer loses what you queued.** Messages sent while a run worked stay visible after Stop: a line the run had not read is marked "not delivered" in the log with Send now and Discard, and one held for after the turn stays in the list, paused.

- **A refused command says which rule refused it and where that rule is lifted.** Every shell command stopped by a safety rule names the rule and the Safety Mode that allows it, and words like shutdown, reboot, halt or wipe only count where they are the command itself, not inside a search, an echo or a commit message.

- **A sub-agent that declines its errand no longer counts as done.** A helper that refuses in German, or says it cannot inspect or trace the code, is recognised at its first step, stops there, and comes back empty with its own words and what it cost, instead of wearing a success tick.

- **A plugin page that fails says why.** When a plugin page's own code stops with an error, the plugin view names the error and the file it came from above the page, instead of leaving its loading placeholder on screen with no explanation.

- **A slash command in the Code window runs when you pick it.** Enter on a command that needs nothing more, such as /cost, /diff, /undo or /stop, runs it straight away, and so does a click on it in the menu; a command that takes text, such as /commit, still waits for it, and Tab only completes.

- **Esc closes every dialog in the Code window.** The context view from /cost, the rename and delete questions, the agent log, the clone, reference and skills pickers, the pull request dialog and the full-page preview all close on Esc and put the cursor back in the message box. Esc with a dialog open never also stops the running turn; a menu open inside a dialog closes first.

- **Skales Code says when no provider is connected.** With no API key saved, the Code window shows the settings hint with Open Settings above the message box, the title bar reads "No provider connected" instead of naming a provider with a green dot, and no model is named until one can answer. Adding a key in Settings takes the hint away without a reload. The row of controls under the message box now wraps onto a second line instead of cutting off its last controls in narrow and split windows.

- **Flow no longer shows a template that Auto is going to ignore.** Switching back to Auto after picking a template clears the template from the start page, because Auto chooses the template itself; picking a template again leaves Auto.

- **A Code session you open again starts at its latest answer.** Reopening a session from the history or after a restart could leave it scrolled to the very first message; it now opens at the end, stays there while late content lays out, and still stops following as soon as you scroll up to read.

- **Emojis without an animation are drawn still without a failed download.** Skales knows which emojis have an animation and no longer asks the network for the others, so the default profile glyph stopped producing a failed request on every page.

- **Skales Code no longer writes a file into your repository to map it.** The map of a project's files and symbols is kept in the Skales data folder instead of a .skales-backup/repo-map.json in the project, so it no longer appears in your git status or in the review of what a session changed. A map left there by an earlier version is removed the next time the project is opened.

- **A code answer that ends in a call is shown, not swallowed.** A Python, JavaScript or shell script whose last line was `main()` or `run()` was taken for a tool call that never ran: the real answer disappeared and a second turn only said it was a false alarm. Code in a fenced block is now always the answer, and a bare call only counts when it names a real tool.

- **Undoing a turn no longer takes its cost off the meter.** /undo, a rollback, an edited question, a deleted answer or a compacted history used to remove the price of the removed turns too, so the session total dropped and a cost limit read less than was actually billed. Money already spent now stays on the session, in the chat, in Code and on the phone.

- **Stop in the chat no longer calls waiting lines delivered.** Lines typed while a turn worked flashed as delivered and vanished when you pressed Stop, although the model never read them. They now stay listed as not delivered, with Send now and Discard, exactly like in the Code window, and after a reload too.

- **Write and Edit rows in Code no longer start with a line of internal bookkeeping.** A code the runner keeps to remember which changes already happened was printed at the top of every Write and Edit row; it is now hidden there, in the chat, in Iris and on the phone.

- **Reading a Code session from the chat counts the files it lists.** For a folder inside a larger repository the summary said "Changed: 0 file(s)" next to five changed paths; the number now comes from the same list, and the line counts are only shown when git sees every listed file.

- **The review panel of a folder inside a bigger repository no longer offers that repository's other work.** It names the repository the folder belongs to, says when that repository ignores the folder, offers no pull request for the whole repository, and under Parallel work lists only the checkouts this session started. Removing one asks first, and a checkout started elsewhere can no longer be removed from here.

- **Jev routes each turn once, only among models you have switched on, and from the start screen too.** With the Advisor Strategy off, its planning and executing models were still offered as choices; they no longer are. The model hint now also appears while typing on the new-chat screen, and a turn that continues (a cut-off answer, a steer, a line you add) keeps the model Jev picked instead of asking and paying again.

- **A specialist from the agent library works under the same helper card as any sub-agent.** Handing a task to a library specialist showed no helper card while it worked, and afterwards its answer appeared as raw markdown in a tool row, also after a reload. The card now appears during the run and after it, the answer is rendered, and the approval says how the specialist runs, as it does for Skales Code.

- **A /btw side question stays beside the work.** Asked while a turn was working, its answer split the turn's steps in two and could reach the model on the next turn through Code, a resumed run, Telegram, WhatsApp or the Buddy. It is now drawn after the turn it was asked in, never enters what the model reads, and may also answer from general knowledge, not only from the conversation.

- **The cost of a turn stands on its answer, not on an empty reply.** What the model router or a continuation request cost was written as an empty message that then looked like a cut-off reply. It is now added to the turn's answer; only a turn without any answer keeps a separate cost row, which is never shown as a reply.

- **The chat no longer sits and waits for a Code session.** After handing work to Skales Code, the assistant watched it with pauses and repeated status checks until the loop guard stopped it. It is now told that the session works on its own, a status check while it works says to answer instead of asking again, and the chat gets a short line with the link when the Code turn it started has ended.

- **Reloading Flow opens the project you were in.** The open project is now part of the window's address, so a reload or a restored window lands in that project instead of on the start page.

- **Four small fixes from the release check.** The approval bar says "1 action needs" and "3 actions need" correctly in every language; Flow shows the price next to its token count like the chat and Code do; opening Settings from the chat no longer lands on an older Code session, because the Code window now remembers its own last session; and a /refine that finds nothing to keep says what the look-back cost.

- **Lio AI shows the same lion mark everywhere it appears.** The sidebar, Flow's doors, Settings and the Add-ons catalog used to draw it differently, once as an unrelated shape and once as a generic icon; all of them now draw the one mark.

- **Switching Flow's mode back to Auto closes that mode's own extra options.** Opening Motion's style picker and then choosing Auto used to leave it open on screen; picking Auto, or any other mode, now closes it, including after switching back and forth several times.

### Changed

- **The Type animation presets look the same in preview and export, every time you seek.** Cascade and Flip Board turn around their own edge, Glitch splits its colours both ways, a looping entrance leaves on its own curve, and a one-shot preview rests for a moment before it plays again. The badge on the featured set reads in your language.
- **Helpers get only what they need.** A team member, a plugin's own agent and a helper step inside a Flow run now work from their own task without your name, your standing instructions or your memory, unless you ask for them. The title, the router and the background review already worked this way and stay so.

- **Flow has no house style any more.** Without a Brand Kit or a style pack, each project is offered a few design directions chosen from its brief and away from the looks of your last projects, and names the one it took. Three similar briefs no longer come back in the same dark look.

- **Your name goes into a Flow design only when the brief asks for it.** "My showreel" or "our company" brings your name or brand in (with memory on) or a marked placeholder (with it off); "a showreel" stays fictional, without your name and without Skales.

- **Settings sections have headings you can find.** Every section of a category starts with its name, its icon in the colour of its category and one line saying what you find there, so a long category no longer reads as one wall. The category list carries the same colours. In the Flat theme, which has no icons, the colour is a short bar beside the heading.

- **Long Settings categories are shorter.** Skales Local, Images & Video, Model profiles, Web search, Places & GIFs, AI labelling, Trash and Network each stand as one line with its own page, and Extensions is one list, each line saying what it holds. A link to one of them opens its page directly.

- **Iris is a sound wave everywhere.** The sidebar, the Settings section and the add-on card show Iris Orbit as a sound wave, and the eye belongs to incognito alone. The chat start page has a button to talk with Iris Orbit right of the incognito eye; the chat header hands a conversation to Iris with the same sound wave. On an incognito chat both stay closed and say why, because Iris keeps its own history.

- **Plugin pages have no second header.** The app's own header and back arrow above a plugin's page are gone, since the page has its own. "Give a job" for a plugin with an agent now sits in the line under the page and in its right-click menu.

- **Setting up an API connector asks first.** When the assistant scaffolds a connector to one of your services from its documentation, you now confirm it on the permission card before it is saved.

- **Built-in agents work like specialists.** The Code Assistant, Data Analyst, Strategic Planner, CTO, Research Analyst and Project Manager, most roles of the team presets and the agents of the organization templates now run on detailed specialist prompts from the open agency-agents library, and they answer in the language you write in. Every such card says where its prompt comes from, with the licence and a link. A prompt you changed yourself stays exactly as you wrote it, and a built-in agent you only pinned a model on picks up the new prompt and keeps your model.

- **The sound wave is the chat's one voice door.** The separate microphone mode in the chat header is gone from the start page, open chats, incognito and the remote view; talking to Skales by voice is Iris Orbit, behind the sound wave. With the Iris Orbit add-on switched off, the sound wave shows how to turn it on in Settings instead of opening another voice mode. Iris Orbit stays closed in incognito chats.

- **Giving a plugin a job happens in the line under its page.** The window that opened over the page is gone; the right-click entry switches to AI does it and puts the cursor in that line.

### Removed

- **Call Mode is gone; Iris Orbit is the one way to talk to Skales.** The phone button in the chat header and its switch in Settings are removed. Talking over an answer to interrupt it is Iris Orbit's Duplex setting under Settings, Voice. A saved setting that had Call Mode switched off keeps the microphone closed until you choose Duplex there; nothing else changes.
