# Writing a post

1. Create a Markdown file in this folder. Its filename is the post slug, for example `making-a-living-portrait.md`.
2. Add the post to `../posts.json` with its `slug`, `title`, `date`, and `description`.
3. Use ordinary Markdown. Images can use site-root paths such as `![Alt text](/assets/my-image.png)`.
4. Mermaid diagrams use a fenced code block marked `mermaid`.

```mermaid
flowchart LR
  A[Markdown] --> B[Blog page]
  B --> C[Published note]
```
