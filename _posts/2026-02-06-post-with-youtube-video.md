---
layout: single
title: "A Post with an Embedded YouTube Video"
date: 2026-02-06 16:00:00 +0000
categories: [blog]
tags: [video, youtube, embed]
excerpt: "This post shows how to embed a YouTube video in your Jekyll site. Works completely static on GitHub Pages."
---

This post embeds a YouTube video using static HTML. The video is rendered at build time—no JavaScript required, so it works perfectly on GitHub Pages.

## The embedded video

{% include video id="dQw4w9WgXcQ" provider="youtube" %}

## How to use your own video

To embed a different YouTube video, replace the `id` with your video's ID:

- From `https://www.youtube.com/watch?v=**VIDEO_ID**` → use `VIDEO_ID`
- From `https://youtu.be/VIDEO_ID` → use `VIDEO_ID`

Example:

```liquid
{% raw %}{% include video id="YOUR_VIDEO_ID" provider="youtube" %}{% endraw %}
```

The theme's video include generates a responsive iframe that works on all devices. Vimeo is also supported: use `provider="vimeo"` with the Vimeo video ID.
