---
title: "Chatting with DAB in the Student Portal"
excerpt: "A detailed tutorial on how to use the student portal to interact with AI agents."
author: "Mochen Yang"
image: 
  path: /images/2025-05-30-student-tutorial/header.webp
  thumbnail: /images/2025-05-30-student-tutorial/thumbnail.webp
categories:
  - Tutorial
---

> If you are an instructor, please feel free to share this article with your students as an "instruction manual" on how to use the student portal.

Welcome to Mentorica.AI! This article will walk you through how to use the student portal to interact with DAB, our AI agents, to support your learning experiences.

Below is a short video to get you on board. Read on if you prefer written instructions!
<iframe width="639" height="346" src="https://www.youtube.com/embed/XM3Iv3YBNf0" title="Mentorica AI: Using the Student Portal" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# Getting Access

Please navigate to [dab.bot](https://dab.bot) and enter your email address. Please make sure to enter the email address you intend to use with Mentorica -- this is often your University email address, or a work / personal email address that you have indicated to your instructor as your preferred credential.
- If you are accessing the portal **for the first time**: you will be prompted to set up your password;
- **For all other logins**: please use the same email address and password to sign in. 

# Student Portal Layout

The student portal has the following key components:

![student portal](../../images/2025-05-30-student-tutorial/student_portal.webp)

- **Course selector** (dropdown menu on the top right corner) allows you to switch between different courses that are using Mentorica;
- Choose a channel from the list of channels to start chatting. Different channels are created by your instructor for different purposes. For example:
    - The #general channel is typically used as a common place for the instructor to send announcements. The #general channel does not have AI agents.
    - You may have a TABot channel where an AI agent can answer your questions about the basic information of the course.
    - You may have one or more assignment channels where you can interact with AI agents specifically designed to provide support for different assignments / tasks. For instance, if you (either individually or as a member of a team) are working on a case called “Case 1”, then you will see a channel named “Case 1”, where you can interact with an AI agent designed for Case 1. 
    - If an assignment channel is set up to be used by a team, then the name of all team members will show up on the left. If you do not see this, it means you are the only student in the channel.

# Chat

To send a message, type it in the chat input box and hit “Send” or Enter on your board. In a group channel with both an AI agent and other students, you can send a message either to the AI agent or to other students, by toggling the AI agent card at the left end of the chat input box. Specifically,
- By default, a message you send will be directed to the AI agent, and the AI agent will respond to your message.
- If you want to send a message only to the other students in the channel, click on the AI agent card to “mute” the AI agent. Then, the agent will not respond to your message. However, the agent will still be aware of your message. In subsequent messages with the agent toggled on, the agent will be able to refer back to conversations you have had with other students. 

Sometimes, the AI agent might return errors or get "stuck" on a request due to glitches in OpenAI's service. We have already implemented automatic recovery mechanisms to reduce disruptions to your chat experiences. In rare instances when automatic recovery does not address the problem, you can manually type “/reset” in a channel to reset the conversation thread with the AI agent. Doing so will create a clean slate and allow you to chat with the AI agent from scratch.
