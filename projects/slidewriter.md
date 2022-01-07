---
title: Slidewriter
layout: page
url: /projects/slidewriter
---

Project url: [slidewriter.io](https://slidewriter.io)

![Screenshot of Slidewriter's default screen showing slide text and the preview](/assets//slidewriter_01.jpg)

When I was working at Jama Software, Engineering had a bi-weekly tradition of giving lightning talks. Anyone could sign up and spend 5 minutes or so presenting on anything they wanted. Putting slides together with the usual tools was still a pain, even when I didn't really care what the slides looked like.

I wanted something that let me just type and the design would be good enough. I also wanted something that knew I was online and recognized urls and just did what I wanted.

Slidewriter is the result. Type Markdown, get a ready-to-go presentation. It has a couple of web-aware niceties that deviate from standard Markdown syntax. If you paste in a YouTube url, for example, it gets converted to a video embed automatically. Images are similar. Instead of the usual image Markdown, you can simply paste a link to the image.kj

The app is built on older versions of React and MobX. Presentations are stored locally in the browser. I experimented with Amazon's Cognito and DynamoDB for another iteration of it, but abandoned it out of a lack of time.
