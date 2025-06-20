---
layout: default # Uses the default layout from your chosen theme
title: AI Agents # HTML title tag
permalink: /agents/ # URL will be yourname.github.io/agents/
---

# My AI Agents

Explore some of the AI agents I've built and deployed on Hugging Face Spaces.

## ✈️ Travel Planner Agent

This agent helps you plan your trips by suggesting itineraries, finding information about destinations, and more!
<br> <!-- Add a line break for spacing before the app -->
<gradio-app src="https://seetaram-r-travel-planner-agent.hf.space"></gradio-app>
<br> <!-- Add a line break for spacing after the app -->
[View on Hugging Face Spaces](https://seetaram-r-travel-planner-agent.hf.space){:target="_blank"}

---

## 📄 Chat With My Resume Agent

Have a conversation with my resume! Ask questions about my experience, skills, and projects.
<br>
<gradio-app src="https://seetaram-r-chat-with-resume.hf.space"></gradio-app>
<br>
[View on Hugging Face Spaces](https://seetaram-r-chat-with-resume.hf.space){:target="_blank"}

---

## 💼 Career Agent

This agent can provide career advice, help with job searching strategies, or discuss industry trends.
<br>
<gradio-app src="https://seetaram-r-seetaram-career-agent.hf.space"></gradio-app>
<br>
[View on Hugging Face Spaces](https://seetaram-r-seetaram-career-agent.hf.space){:target="_blank"}

<br>
<hr>

**Technical Note:** These applications are embedded directly from Hugging Face Spaces. Loading times may vary.
The `<gradio-app>` web component script is usually loaded automatically by the component itself.
If you face issues, you might need to explicitly add `<script type="module" src="https://gradio.s3-us-west-2.amazonaws.com/4.16.0/gradio.js"></script>` (or the latest version) to your theme's layout, typically in the `<head>` section of `_layouts/default.html` if your theme doesn't handle it. However, try without it first.
