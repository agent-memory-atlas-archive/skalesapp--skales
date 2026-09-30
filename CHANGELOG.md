# **Changelog**

All notable changes to Skales will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),

and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## v12.9.46 - Mend

**A release that mends what 12.9.45 left loose: Windows updates go through again, a finished answer stays on screen, and Flow stops teaching one look.**

Mend is the second release in two days, and it is mostly repairs. On Windows an update could stop with "Skales cannot be closed" although nothing was running: an older version had written files with paths too long for Windows into the program folder, and the old uninstaller could not move them. The installer now clears those files first, Skales removes anything it did not ship when it starts, and nothing installs into the program folder any more.

In the chat, an answer that was followed by another step no longer disappears, Ollama keeps its thinking on answers with a picture, a leading "Thinking Process" folds away, and Max effort stays selected. Backup imports say why they stopped, and background motion calms down on integrated graphics, behind open popups and when it is switched off.

Flow gets more room. Collage and Skales Visuals start without an image service, the right craft packs load for each kind of work, motion scenes can leave through their own exits, captions are burned in, and a free GSAP lane sits beside the standard engine, rendered frame by frame through a virtual clock. The browser view in the chat now shows the agent's own step pictures with the target marked before each click, and Skales Local says whether it really runs on the graphics card.


### Added

- **Motion exports and contact sheets share a virtual clock for pages without a frame-seeking hook.** Animation frames, timers and web animations replay from a cold document for repeated or backward seeks, while authored Engine and GSAP hooks retain control. Asset and playback failures keep their actual cause.

- **Flow Motion can author free GSAP compositions alongside its standard engine.** Paused timelines share the frame, readiness and local-asset contract, with explicit ownership for captions drawn by the page. The inspector explains and blocks GSAP animation edits while preserving text, layout and guarded history operations.

### Fixed
-- **Transition regression tests verify the configured isolated data directory instead of its folder name.** Persisted tool and editor transitions retain their twelve-cycle audio, overlay, caption and output checks under the standard test wrapper.

- **Standalone packages explicitly include the Motion contract parser and reject a missing parser entry.** Acorn remains pinned to its existing production version; regression checks retain both Engine and GSAP seeds and verify data isolation through the configured directory.

- **Browser stream and chat-placement regression checks preserve isolation and visible labels across the current code paths.** Tests validate the configured data directory rather than its folder name and follow translated browser or desktop labels through their visible and image descriptions.

- **Browser click regression checks follow shared outcome values without losing return-path coverage.** The scanner verifies the immutable measured state on both ref outcomes and retains all six click returns, unchanged-click failures and publication checks.

- **Chat continuation and goal-completion regression checks follow the current persistence paths.** Tests inspect the actual carry blocks and exercise both completion guards through repeated blocked and successful visits, preserving the text, reasoning, usage and task-completion invariants.

 **Chromium installers never run inside the application folder.** Windows extended paths, casing and UNC aliases share one guard before either bundled or npm child starts; bundled module lookup remains in the installed package while its working directory stays outside it.


- **Startup removes unshipped entries from the extracted server dependencies.** A shipped inventory survives archive removal and preserves scoped packages, nested dependencies and legitimate symlinks. Missing or invalid inventories leave files untouched and log the reason; extended Windows paths remain confined to the standalone dependency tree.

- **Windows updates remove old extracted server dependencies before the previous uninstaller moves them.** Extended paths handle runtime-added packages beyond MAX_PATH, including manually started updates. The new installation restores its dependencies from the shipped archive on first launch.

- **The browser view follows the agent’s own step images and marks its chosen target before a click.** Ref, semantic and vision clicks share before/after evidence, bounded history and restart-safe stream identities. Stale polls cannot replace a newer run, and publication remains explicitly unconfirmed without proof.

- **Flow footage edits keep long transcripts, original sound and the chosen shortform treatment.** Explicit hooks lead the cut, word captions share the existing subtitle path, and zoom, whip and glitch transitions persist through tool and editor changes. Empty plan revisions clear unchanged video tracks while preserving independent music, overlays and the selected output format.

- **Motion scenes can hand over through authored exits without an automatic transition.** Three cubic-bezier eases and slide-left/zoom clip envelopes keep frame seeking deterministic, while composition checks and contact-sheet review use the same animation vocabulary.

- **Motion exports burn timed captions from composition clips and local speech tracks.** Subtitle timing follows the current project, overlapping authored captions take precedence, and the original composition stays editable without duplicate captions in the export. Unreadable caption sources report their actual cause before rendering starts.

- **Computer control uses bounded screenshots and measures actions instead of repeated pictures.** Model images share the existing 1024-pixel limit, retain exact display coordinates and carry their revision from find to click. Screenshot-only loops keep their no-progress state after resume without affecting a new user request or genuine file work.

- **Content reports retain the original answer provider and model.** The context includes redacted attribution before excerpt trimming; missing historical metadata stays unknown and queued retries preserve the original snapshot.

- **Completed answers stop even when an old checklist still has open items.** Actual promises to act still continue, and output-limit continuations retain their complete text, reasoning and usage without a stale checklist restarting them.

- **Max reasoning effort remains selected after reopening a conversation.** Saving the per-session override now accepts Max alongside the other effort levels and leaves the session model, instructions and composer unchanged.

- **Background motion respects integrated graphics, saved preferences and open popups.** Electron supplies measured GPU information and feature status for defaults and diagnostics, while overlapping popups pause the shared ambient layers until the last one closes.

- **Local models expose their context and GPU-layer presets directly on each installed model.** Edits save through the model’s installed identity and synchronize the runtime after confirmation; queued writes, draft inputs and row-level errors protect rapid changes and failed restarts.

- **Skales Local reports GPU use only after measured offload.** An accelerated build without a loaded measurement stays unknown, and zero-layer hints use the active model’s own preset instead of another model’s request.

- **Plugin pages keep their mode controls unobstructed.** The embedded page has an accessible name without a page-wide hover tooltip covering the footer; hints on individual controls keep using the shared tooltip host.
- **Computer screenshots identify the screen they show.** The live card and its accessible image label distinguish desktop captures from browser frames, including action changes that reuse the same image URL.
- **Explicit thinking stays in the reasoning fold.** Leading Thinking Process and Thinking labels are separated from the answer for every model, including live replies and provider reasoning channels. Quoted examples and ordinary Thinking prose remain visible, and continued replies retain their text, traces and usage.

- **Replies survive automatic continuation.** A response followed by another step stays in the saved conversation with its reasoning and usage, including interrupted continuations. Complete replies share one bubble while output-limit fragments join without repeated text.
- **Flow motion follows the brief instead of repeating one entrance and transition.** The example starts with a cut, while guidance and the motion skill choose entrances, holds, exits and scene boundaries by their purpose and character. The seekable runtime and render validators stay intact.
- **Flow and Studio load the craft packs for the work they actually make.** Local video visuals receive motion guidance, collages and image visuals receive frontend and print guidance, and footage gets cutting plus motion guidance. Studio and chat visual generation append the full enabled skill texts on image and video paths.
- **Collage and Skales Visuals start with their local renderer.** Image compositions need Playwright and local video needs Playwright plus FFmpeg; media keys are checked only for explicitly requested generated assets. Both Flow start paths show refusals and thrown errors while releasing their start controls.
- **Background motion now stops consistently when it is disabled.** The mood bar follows Background animation, reduced motion and window focus while keeping its reading visible. Popups use one app background, and reduced-motion CSS priorities apply correctly.
- **Backup import failures now explain why they stopped.** A rejected restore or unreadable ZIP shows its reason in Settings and releases the import button for another attempt.
- **Ollama keeps its reasoning on image answers.** Native image turns now retain the model's thinking after the response is saved, including turns that call a tool.

### Changed

- **Code-window accent sharing is verified across window and appearance changes.** Focused regression coverage checks the existing shared origin, storage identity, theme policy and listener lifecycle without changing the established accent behavior.
