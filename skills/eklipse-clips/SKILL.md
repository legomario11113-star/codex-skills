---
name: eklipse-clips
description: Find, review, download, and make TikTok montages from the user's Eklipse gaming clips, including GTA clips. Use for Eklipse clip selection or editing; not for unrelated video sites.
---

# Eklipse clips

Use the user's signed-in Eklipse session in the browser available to this chat. Read the relevant browser skill before using that browser. If the user supplies a clip or stream title, search for that first; if they leave the choice open, select one suitable clip and briefly say why.

## Finding clips

In Eklipse, open **Library → Streams**. Find the stream by game and title, then **Watch Clips**. A stream page shows clip titles, durations, scores, and a player; use these to narrow candidates. For GTA VI, an observed example was a stream titled “GTA 6 с Дариночкой” with clips under `Grand Theft Auto VI`. Treat this as an example, not a permanent stream ID or assumption about future requests. The broad **Library → Clip → Stream Highlights** list may start with recent clips from another game, so stream selection is often faster.

When choosing a clip, prefer a clear, short moment with a strong score unless the user specifies other criteria. Preview the actual footage and listen to the relevant audio before selecting a moment. AI-generated titles and scores can misdescribe the clip. Do not claim to have reviewed footage or speech if only metadata or sample frames were inspected.

For this user's GTA recommendations, three examples they liked were `general_highlight_moment_54`, `_49`, and `_94` from stream `144360077` (2026-11-19). They clarified that **erotic content within roleplay** is the defining feature. Prioritize scenes where the adult or suggestive situation actually happens on screen alongside RP dialogue and reactions. A clip merely mentioning a strip club, such as a game restart before reaching it, did not match. Do not substitute generic chases, high scores, or ordinary RP banter for this preference. Current preference: suggestive RP is fine, but exclude any shot showing a bare torso. Check the entire chosen segment, including the facecam, for this before delivery. If a suitable scene cannot meet that limit, choose another GTA topic. Treat new feedback as stronger evidence than these examples.

## Downloading

On the selected stream clip, use **Download**, then **No, Just Download** if Eklipse offers conversion to vertical format. The site may show “Clip downloaded!” while the browser is still completing the file transfer. Where browser tooling supports it, register a download event before the final click and obtain its completed local path; otherwise verify the actual file exists. Keep the original file. When the user asks for a montage, do not use Eklipse's Convert, AI Edit, or editor to produce the final video; Eklipse is the source library. A request for a TikTok-ready montage authorizes local editing, not conversion in Eklipse.

Copy the verified original video into the current task's user-facing outputs directory when the environment provides one. Check its size and, when possible, duration. Return a link or inline video to the local deliverable. Do not publish, schedule, upgrade, or post the clip unless the user asks. Dismiss any upsell after download.

## TikTok montage

Edit the verified downloaded original with local video tools. Inspect footage across the full intended segment and listen to its audio before writing captions or choosing cuts. Trim idle setup, use only events actually shown, and do not treat an Eklipse title as a description of the footage. If speech cannot be reliably transcribed, omit speech subtitles or clearly use separate editorial text; never invent dialogue. Check that the final video actually differs from the original in the intended ways.

The user approved a 50-second, 9:16 GTA montage with the streamer's face in a top panel, gameplay below, and large Russian speech subtitles burned into the video when the words can be verified against the audio. For future similar requests, use this as a style preference, adapting timing and crop to the actual clips. The user specifically disliked a game panel that showed the streamer a second time and a white line between panels. Keep the in-game character's face visible, preserve the footage's aspect ratio where possible, and inspect sample frames from the beginning, middle, and end of the finished file before delivery. Also verify duration, 9:16 dimensions, audible audio, and that no duplicate facecam or unwanted bare torso appears. Read [the approved layout notes](references/tiktok-layout.md) when editing clips that already contain a webcam overlay.

Keep every finished short video at **60 seconds or less**. Prefer **20–30 seconds** when the setup, payoff, and reaction fit without losing clarity; the approved 50-second montage is a layout example, not a duration target. The main goal is to hold attention through the first **3–4 seconds**: begin close to the surprising action or line, cut idle setup and pauses, and put the first verified subtitle or clearly editorial hook on screen promptly. Check the opening as a viewer would before rendering the final file. Preserve enough context for the hook to make sense rather than shortening mechanically.

Use current browser state and visible controls. Never reuse tab IDs, element indices, stream IDs, or download paths from earlier sessions. If Eklipse requires sign-in, leave the sign-in page available for the user and resume once they have signed in.

