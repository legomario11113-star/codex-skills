# Approved GTA TikTok layout

The user liked a montage of three moments from stream `144360077`: 1080×1920, 30 fps, about 50 seconds, facecam on top, game below, native game audio, and readable Russian subtitles. The user then requested a wider first game crop to include the main character's face, removal of the duplicate webcam embedded in that game crop, and no white divider. The corrected version was approved.

For 1920×1080 source clips with this same composition, the validated rendering used:

- Top panel: crop the source webcam from the upper-left 500×270 pixels and scale it to 1080×600. Cropping at 270 rather than 280 removed a white edge already present at the bottom of the webcam image.
- Game panel: 1080×1320. For the first scene, remove the embedded webcam region (`delogo` around x=1, y=1, w=500, h=280), then crop the source game at x=350, y=0, w=1400, h=1080 and scale proportionally to 1080×833. Place it at the top of the game panel; fill the remaining area with a blurred copy of the game frame. This kept the in-game character's face visible without showing the streamer twice. For later scenes, the source webcam was outside the selected game crop, so no removal was needed.
- Stack the panels directly. Do not add a bright divider. Crop any source border from the webcam panel before stacking.
- Position burned-in subtitles over the game or blurred lower area, away from TikTok's bottom controls. Subtitle words came from speech recognition and needed review against noisy game audio.

The coordinates above are specific to these source clips, not universal defaults. Before rendering, inspect the source webcam bounds and the important game action. Check frames early and late in each segment for a duplicate webcam, faces cut off, subtitle readability, and a clean panel seam. Confirm the finished MP4 has 9:16 video and audio.

