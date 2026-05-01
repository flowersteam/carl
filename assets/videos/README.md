# Video assets

Drop the following `.mp4` files into this directory. Each is referenced by
`index.html` as an autoplay, muted, looping, playsinline video (the same
pattern Sakana AI uses for their blog videos — see
`https://sakana.ai/asal/`).

All videos should be H.264 + AAC, muted-friendly, and compressed for web
(target ~2–8 MB each; aim for ~1–2 Mbps bitrate at 720p or smaller). Loop
points matter: trim so the first and last frames match to avoid a visible
seam when the video restarts.

## Expected files

| filename                           | used for                                                 | suggested aspect |
|------------------------------------|----------------------------------------------------------|------------------|
| `cover_reel.mp4`                   | hero montage at the top                                  | 1:1              |
| `framework_loop.mp4`               | closed-loop framework diagram (animated)                 | 16:9             |
| `soliton_creation_grid.mp4`        | grid of solitons emerging across many update rules       | 16:9 or 4:3      |
| `soliton_baseline_comparison.mp4`  | side-by-side CARL vs. heuristic baselines                | 16:9             |
| `novel_rules_atlas.mp4`            | solitons discovered on unseen convolutional kernels      | 16:9 or 4:3      |
| `steering_grid.mp4`                | directional steering across solitons and directions      | 16:9             |
| `maze_human_in_loop.mp4`           | main human-in-the-loop maze navigation clip              | 16:9             |
| `maze_low_cost.mp4`                | low action-cost maze traversal (fast)                    | 1:1 or 4:3       |
| `maze_high_cost.mp4`               | high action-cost maze traversal (cautious)               | 1:1 or 4:3       |

Until these files exist, the page renders a diagonal-stripe placeholder
where each video will appear, labelled with the expected filename. That
makes it easy to swap in final assets without touching `index.html`.
