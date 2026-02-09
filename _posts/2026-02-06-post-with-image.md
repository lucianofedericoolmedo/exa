---
layout: single
title: "A Post with an Image"
date: 2026-02-06 14:00:00 +0000
categories: [blog]
tags: [image, example, jekyll]
excerpt: "This post demonstrates how to include an image in your Jekyll content."
header:
  image: /assets/images/post-featured-image.jpg
  image_description: "Featured image for this post"
  caption: "Place your caption here"
---

This is a second post that includes an image. The image appears in the header above and can also be displayed within the content.

## About the image

The header image is loaded from `assets/images/post-featured-image.jpg`. Simply place your JPG file there with that exact filename and it will display automatically.

## More content

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Image in content

The image below is displayed at a controlled size (max 600px wide) within the post body:

![Featured image]({{ "/assets/images/post-featured-image.jpg" | relative_url }}){: .post-image}

You can add more text after the image. The styling ensures the image is responsive and doesn't overflow on smaller screens.
