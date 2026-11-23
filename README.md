<p align="center"><img src="icon.png" width="120" alt="Voilà app icon"></p>

<h1 align="center">Voilà</h1>

<p align="center"><b>A French verb trainer that works without a connection,<br>and does not get the grammar wrong.</b></p>

> **This is a showcase.** The source code is private, because Voilà is built around one person's progress. Here is what it does and why it is built the way it is.

Voilà is where I practise French conjugation, on my phone or my laptop. The interface is in English, with a full Hebrew toggle. French is always the content.

Every exercise is made and checked on the device itself, so it answers instantly and works on a plane. No AI decides, while I practise, what a verb should look like.

## The one rule: the grammar is never wrong

In this project, a bug in the game is tolerable, and an error in the grammar is not. Almost everything unusual about how Voilà is built follows from that one sentence:

- **Twelve checks** run before anything reaches the app.
- **Hundreds of deliberately wrong French examples** prove that those checks refuse what they should.
- **Every release is sealed.** It carries a fingerprint of every byte, and the app refuses to start from one that was changed afterwards.
- **An interrupted update changes nothing.** The previous version keeps running until the new one is complete.

## What is inside

- **17 tenses across 4 moods,** over a dictionary of about 7,800 verbs. Nothing is locked.
- **Verb families.** Verbs are grouped into 7 families and 74 sub-families, so I learn the pattern and not only the list.
- **Spaced repetition** that follows each verb, tense and person separately, so what is shaky comes back and what is solid gets out of the way.
- **Key verbs.** I tick the five I want to master, and they come up far more often.
- **Around the drill:** a full cheat sheet, short lessons that teach first, reading rules and sounds, decks of sentences to learn by heart, and word practice for vocabulary.
- **Every answer is explained.**

## A look

Real screens of the app, captured on a fresh install with an empty database, so they show no personal data.

**On the computer:** the verb tables in Practice, where I type any verb and see it in every tense, and the cheat sheet, a reference for every French tense with its use, its formation and examples.

<p align="center"><img src="screens-desktop-verbs.png" alt="Verb tables in Practice on a computer: a verb typed in, shown in every tense" width="100%"></p>

<p align="center"><img src="screens-desktop-cheatsheet.png" alt="The cheat sheet on a computer" width="100%"></p>

**On the phone:** the conjugation setup, quick conjugation, and word practice for vocabulary.

<p align="center"><img src="screens-phone.png" alt="Conjugation, Quick conjugation and Word practice screens on a phone" width="100%"></p>

## A coach inside the app

A French coach, a separate AI agent, writes my learning plan and reports on how I am doing. They appear in a personal area in the app, behind the profile circle on every screen: progress by level, the road to an exam, and more.

The coach and the app agree on a written format, so only well-formed reports ever show up. The area is private to me, and the last copy is kept on my phone, so it opens even without a signal.

## How I built it

With a team of AI agents: one plans, others build, one tests, one reviews security, one ships. I am the human in the loop who decides. Every release leaves a dated restore point behind.

## Want to see it work?

The code stays private, but I am happy to show you Voilà live.

<p align="center">Built by <a href="https://github.com/einavtayari">Einav</a>, the human in the loop.</p>
