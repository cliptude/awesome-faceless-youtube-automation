# Awesome Faceless YouTube Automation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Tools, footage sources, policies and workflows for running a faceless YouTube channel: documentaries, Top 10s, explainers and narrated stories, made by hand, with AI, or with AI agents.

A faceless channel publishes videos without the creator on camera: narration over footage, maps, charts, animation or an AI presenter. This list collects what you need to make those videos well and keep the channel monetized.

Contributions are welcome. Read the [contribution guidelines](CONTRIBUTING.md) first.

## Contents

- [Rules first: YouTube policies](#rules-first-youtube-policies)
- [Niche and topic research](#niche-and-topic-research)
- [Research and scriptwriting](#research-and-scriptwriting)
- [Voiceover](#voiceover)
- [Free and public-domain footage](#free-and-public-domain-footage)
- [Paid stock footage](#paid-stock-footage)
- [Music and sound effects](#music-and-sound-effects)
- [Editing and motion graphics](#editing-and-motion-graphics)
- [Captions and transcription](#captions-and-transcription)
- [Thumbnails](#thumbnails)
- [AI video generators](#ai-video-generators)
- [AI agents and MCP servers](#ai-agents-and-mcp-servers)
- [Publishing and automation](#publishing-and-automation)
- [Analytics](#analytics)

## Rules first: YouTube policies

Read these before automating anything. Channels lose monetization for mass-produced, repetitive or reused content, not for using AI.

- [YouTube channel monetization policies](https://support.google.com/youtube/answer/1311392) - What qualifies for the Partner Program, including the rules on repetitive and reused content.
- [YouTube Partner Program overview](https://support.google.com/youtube/answer/72851) - Eligibility requirements and how to apply.
- [Disclosing altered or synthetic content](https://support.google.com/youtube/answer/14328491) - When you must label realistic AI-generated people, places or events.
- [Fair use on YouTube](https://support.google.com/youtube/answer/9783148) - How YouTube treats commentary, criticism and other fair-use excerpts.

## Niche and topic research

- [Google Trends](https://trends.google.com/) - See whether interest in a topic is rising, seasonal or fading.
- [Social Blade](https://socialblade.com/) - Public growth stats for channels in your niche.
- [vidIQ](https://vidiq.com/) - Keyword research, competitor tracking and title ideas.
- [TubeBuddy](https://www.tubebuddy.com/) - Keyword explorer, A/B tests for thumbnails and titles.
- [NexLev](https://www.nexlev.io/) - Niche finder built for faceless and automation channels.

## Research and scriptwriting

- [Wikipedia](https://www.wikipedia.org/) - A starting point for dates, names and sources; follow its citations before you quote a number.
- [Perplexity](https://www.perplexity.ai/) - Web search with cited answers for fact-finding.
- [Claude](https://claude.ai/) - Long-form research and narration drafting.
- [ChatGPT](https://chatgpt.com/) - Outlines, hooks and script drafts.

## Voiceover

- [ElevenLabs](https://elevenlabs.io/) - Natural text-to-speech, voice design and cloning.
- [OpenAI text to speech](https://platform.openai.com/docs/guides/text-to-speech) - TTS through the OpenAI API.
- [Cartesia](https://cartesia.ai/) - Low-latency, expressive text-to-speech.

## Free and public-domain footage

Check each file's license, and be careful with recognizable people, brands and logos.

- [Pexels Videos](https://www.pexels.com/videos/) - Free stock video under the Pexels license.
- [Pixabay](https://pixabay.com/videos/) - Free stock video, images and music.
- [Wikimedia Commons](https://commons.wikimedia.org/) - Millions of freely licensed photos, maps and diagrams; licenses vary per file.
- [Internet Archive: Moving Image Archive](https://archive.org/details/movies) - Films, newsreels and home movies, many in the public domain.
- [Prelinger Archives](https://archive.org/details/prelinger) - Twentieth-century ephemeral and industrial films.
- [NASA Image and Video Library](https://images.nasa.gov/) - Space and Earth imagery, generally not copyrighted.
- [Library of Congress: Free to Use and Reuse](https://www.loc.gov/free-to-use/) - Curated public-domain photos and documents.
- [US National Archives Catalog](https://catalog.archives.gov/) - Government photos, film and records.

## Paid stock footage

- [Storyblocks](https://www.storyblocks.com/) - Subscription stock video, audio and images.
- [Envato Elements](https://elements.envato.com/) - Subscription stock footage, templates and music.
- [Shutterstock](https://www.shutterstock.com/video) - Large stock video library, licensed per clip or by plan.
- [Getty Images](https://www.gettyimages.com/) - Editorial and archival footage of real events.

## Music and sound effects

- [YouTube Audio Library](https://studio.youtube.com/) - Free music and effects cleared for YouTube, inside YouTube Studio.
- [Epidemic Sound](https://www.epidemicsound.com/) - Subscription music cleared for YouTube.
- [Artlist](https://artlist.io/) - Subscription music and sound effects.
- [Freesound](https://freesound.org/) - Community sound effects under Creative Commons licenses.

## Editing and motion graphics

- [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) - Professional editor with a free version.
- [CapCut](https://www.capcut.com/) - Quick editor with templates and auto captions.
- [Descript](https://www.descript.com/) - Edit video by editing the transcript.
- [Remotion](https://www.remotion.dev/) - Make videos with React; good for programmatic charts, maps and titles.
- [FFmpeg](https://ffmpeg.org/) - Command-line tool behind most video automation.
- [Blender](https://www.blender.org/) - Free 3D modelling and animation.

## Captions and transcription

- [Whisper](https://github.com/openai/whisper) - Open-source speech recognition with word timestamps.
- [whisper.cpp](https://github.com/ggml-org/whisper.cpp) - Fast local Whisper inference on CPUs and Apple Silicon.

## Thumbnails

- [Photopea](https://www.photopea.com/) - Free browser photo editor that opens PSD files.
- [Canva](https://www.canva.com/) - Templates and quick layouts.
- [Figma](https://www.figma.com/) - Design and test thumbnail variants side by side.

## AI video generators

Tools that turn a prompt or script into a finished video.

- [Cliptude](https://cliptude.com/) - 6–60 minute faceless documentaries and Top 10s with voiceover, real footage, animated maps and charts.
- [InVideo AI](https://invideo.io/) - Prompt-to-video with stock footage and voiceover.
- [Pictory](https://pictory.ai/) - Turns scripts and articles into short videos.
- [VidRush](https://vidrush.ai/) - Long-form faceless video generation.
- [makeaicreator](https://makeaicreator.com/) - Consistent AI presenter with a locked face and voiceover for faceless channels.

## AI agents and MCP servers

Let an AI agent (Claude, ChatGPT, Codex and others) research, plan and produce videos through the [Model Context Protocol](https://modelcontextprotocol.io/).

- [Cliptude MCP](https://github.com/cliptude/cliptude) - Remote MCP server and CLI: an agent plans every shot of a documentary and Cliptude voices, sources and renders it.
- [Cliptude skills on ClawHub](https://clawhub.ai/mwitiderrick/skills/cliptude) - Agent skills for making Cliptude videos from OpenClaw and other agents.

## Publishing and automation

- [YouTube Data API](https://developers.google.com/youtube/v3) - Upload videos, set metadata and manage playlists programmatically.
- [n8n](https://n8n.io/) - Open-source workflow automation for publishing pipelines.
- [Postiz](https://postiz.com/) - Open-source scheduler for cross-posting shorts and clips.

## Analytics

- [YouTube Studio analytics](https://studio.youtube.com/) - Retention, click-through rate and traffic sources for your own videos.
- [Social Blade](https://socialblade.com/) - Track competitors' subscriber and view growth.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
