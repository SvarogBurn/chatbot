# MoveUs Landing Page

A static (old) landing page for **MoveUs**, an app that connects people for sports and physical activity. The page presents the product, embeds a support assistant, and collects beta signups. Made for a simple chatbot school project.

## What it contains

- A single-page site (`index.html`) describing MoveUs and its main ideas: finding activity partners, organizing events, and matching people by skill level.
- An embedded **Voiceflow** assistant that answers visitor questions.
- A **Google Forms** link for beta signup.
- An `assets/` folder for images and supporting files.

## How the assistant works

The assistant is a Voiceflow widget, loaded through Voiceflow's runtime. That means it is scripted through a visual conversation builder rather than a large language model. Replies follow flows that were designed by hand, so the behavior is predictable and does not call out to an LLM. If you are looking for an example of LLM integration, this is not that. It is a straightforward embed of a hosted, rule-based bot.

## Tech

- Plain HTML, CSS, and JavaScript, no framework and no build step
- Voiceflow web chat widget
- Google Forms for signup collection

## Running it

Open `index.html` in a browser, or serve the folder with any static file server. There is no backend to configure. The Voiceflow widget loads from its own runtime, so the assistant needs an internet connection to respond.

## Status

This is a small school project. It works as a landing page and a demo of embedding a hosted assistant. It is not actively maintained.
