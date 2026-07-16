---
theme: geist
colorSchema: dark
title: How To Guide Engineers In The Age Of AI
class: text-center
transition: slide-left
layout: cover
background: /cover.jpg
---

# How To Guide Engineers In The Age Of AI

---
layout: statement
class: text-center
---

<div class="uppercase tracking-widest text-sm">Why talk about this at all?</div>

# AI changed education

<!--
AI doesn't only change work, it also changes the entire education system. Schools already have problems with this. 
In general, it has changed how we learn. So this also has an impact on how we guide other engineers.
-->

---
layout: image-left
image: /me.jpg
class: flex flex-col justify-center
---

# Who am I?

<div class="flex flex-col gap-4 mt-4 text-xl">
  <div class="flex items-center gap-3"><div class="i-carbon-book" /> Epic fantasy reader <span class="opacity-50 text-base">(Brandon Sanderson!)</span></div>
  <div class="flex items-center gap-3"><div class="i-carbon-music" /> Salsa &amp; bachata dancer</div>
  <div class="flex items-center gap-3"><div class="i-carbon-education" /> Teacher</div>
  <div class="flex items-center gap-3"><div class="i-carbon-user-certification" /> Lead Engineer at Keylane</div>
</div>

<!--
Main thing to highlight is that I have teaching experience (educational minor + giving courses at Keylane). I guide many
Engineers of different levels, and I am in general interested in these kind of topics. I think about them,
talk about them, and have lots of experience. That makes me suited for talking about this topic.
-->

---
layout: image-right
image: /ai.jpg
class: flex flex-col justify-center
---

# Usage of the word "AI"

<div class="flex flex-col gap-7">
  <div>
    <div class="uppercase tracking-widest text-sm opacity-50 mb-1">Chat</div>
    <div class="text-2xl">ChatGPT · Claude</div>
  </div>
  <div>
    <div class="uppercase tracking-widest text-sm opacity-50 mb-1">In the editor</div>
    <div class="text-2xl">Codex · Claude Code</div>
  </div>
</div>

<!--
The word "AI" is used in such a broad concept, where the general meaning (by non-technical people) is often related to
LLMs and the related tooling. I will use it as such as well. Not everybody might be on the same line or use the same 
words, so good to clarify this. If certain words become mainstream, I should switch to these words.

Also good to mention which tools I have the most experience with, just in case.
-->

---
layout: cover
background: /code.jpg
class: text-center
---

<div class="uppercase tracking-widest text-sm opacity-70 mb-3">Goal</div>

# Help them become a better engineer

---
layout: cover
background: /understanding.jpg
class: text-center
transition: fade
---

# Focus on understanding

---
layout: center
class: text-center
---

# Bloom's Taxonomy

<div class="flex gap-10" style="height: 22rem">

  <!-- Pyramid -->
  <div class="shrink-0 h-full" style="width: 10rem; clip-path: polygon(100% 0%, 100% 100%, 0% 100%)">
    <div class="flex flex-col h-full gap-1">
      <div class="flex-1" style="background: rgba(255,255,255,0.12)"></div>
      <div class="flex-1" style="background: rgba(255,255,255,0.19)"></div>
      <div class="flex-1" style="background: rgba(255,255,255,0.26)"></div>
      <div class="flex-1" style="background: rgba(255,255,255,0.33)"></div>
      <div class="flex-1" style="background: rgba(255,255,255,0.40)"></div>
      <div class="flex-1" style="background: rgba(255,255,255,0.47)"></div>
    </div>
  </div>

  <!-- Steps -->
  <div class="flex flex-col gap-1 text-left">
    <div class="flex-1 flex flex-col justify-center">
      <div class="text-2xl font-bold leading-tight">Create</div>
      <div>Design a new Spring Boot service from scratch</div>
    </div>
    <div class="flex-1 flex flex-col justify-center">
      <div class="text-2xl font-bold leading-tight">Evaluate</div>
      <div>Decide if logic belongs in the controller or the service</div>
    </div>
    <div class="flex-1 flex flex-col justify-center">
      <div class="text-2xl font-bold leading-tight">Analyze</div>
      <div>Trace a request through controller, service, repository</div>
    </div>
    <div class="flex-1 flex flex-col justify-center">
      <div class="text-2xl font-bold leading-tight">Apply</div>
      <div>Build a REST endpoint backed by a repository</div>
    </div>
    <div class="flex-1 flex flex-col justify-center">
      <div class="text-2xl font-bold leading-tight">Understand</div>
      <div>Explain how Spring injects a @Service bean</div>
    </div>
    <div class="flex-1 flex flex-col justify-center">
      <div class="text-2xl font-bold leading-tight">Remember</div>
      <div>Recall what @RestController and @Autowired do</div>
    </div>
  </div>
</div>

<!--
Understanding is one of 6 steps. It is crucial that you can only apply something that you understood. Sure, you can 
often do something without understanding it (following a manual for example). But in general, quality will be higher 
(and it will also feel better) if you understand what you are doing.
-->

---
layout: statement
class: text-center
---

# Apply &ne; understanding

<div class="mt-6 text-2xl opacity-70">So how do you check?</div>

<!--
Bloom's Taxonomy showed that you need to understand something to apply it. But nowadays, seeing it applied is not a 
good indication anymore for understanding. Result was never equal to understanding, but in some cases it was a good 
indication. If somebody programmed a  feature, then it is pretty clear they understood the design and how to 
implement the feature. Good enough.

These days, it could have been the result of a prompt, which could be generated without any understanding.
-->

---
layout: image-right
image: /talk.jpg
class: flex flex-col justify-center
---

# Talk to them

Ask questions. Let them explain.

<!--
Everything is about learning. A person learns in different ways. To know if they learned something, you need to test 
them in some way. Testing doesn't mean having them do an exam, but just talking with them about the code should 
quickly show whether they understood it or not.

This is now even more crucial than before.

Note: even if they copied it from AI, they might still understand.
-->

---
layout: center
class: text-center
---

# Review chat history

<div class="mt-10 flex justify-center gap-12">
  <div class="px-5 py-4 text-xl rounded-2xl" style="background: rgba(255,255,255,0.20)">Fix it. Make no mistakes.</div>
  <div class="px-5 py-4 text-xl rounded-2xl" style="background: rgba(255,255,255,0.20)">Help me understand how this works.</div>
</div>

<!--
I think this is THE best way to see if they understood a topic. Their chat history shows you HOW they use AI: are they 
outsourcing the thinking ("fix it, make no mistakes") or using it to learn ("help me understand how this works")?

They might be scared to share it though, because it is so personal. Sharing is sometimes technically also a bit more 
difficult if it is split up in different chats or when using a desktop app. Figure out a way together. It is new 
technology and everyone does it differently. You might learn something from it too!

This "how" is exactly what the next part is about.
-->

---
layout: cover
background: /how.jpg
class: text-center
transition: fade
---

# Guide <u>how</u> they use AI

---
layout: center
class: text-center
---

# What the research shows

<div class="mx-auto mt-8 flex flex-col gap-3" style="width: 42rem">

  <div class="flex items-center justify-between px-6 py-4 rounded-xl text-left" style="background: rgba(74,222,128,0.13); border: 1px solid rgba(74,222,128,0.45)">
    <div>
      <div class="text-2xl font-bold">AI as a mentor</div>
      <div class="opacity-70">"Help me understand how this works."</div>
    </div>
    <div class="flex items-center gap-2 uppercase tracking-widest text-xs opacity-80"><div class="i-carbon-arrow-up" /> Better understanding</div>
  </div>

  <div class="flex items-center justify-between px-6 py-4 rounded-xl text-left" style="border: 1px dashed rgba(255,255,255,0.35)">
    <div>
      <div class="text-2xl font-bold">No AI at all</div>
      <div class="opacity-70">The baseline</div>
    </div>
    <div class="uppercase tracking-widest text-xs opacity-50">Baseline</div>
  </div>

  <div class="flex items-center justify-between px-6 py-4 rounded-xl text-left" style="background: rgba(248,113,113,0.13); border: 1px solid rgba(248,113,113,0.45)">
    <div>
      <div class="text-2xl font-bold">AI as an answer machine</div>
      <div class="opacity-70">"Fix it. Make no mistakes."</div>
    </div>
    <div class="flex items-center gap-2 uppercase tracking-widest text-xs opacity-80"><div class="i-carbon-arrow-down" /> Worse understanding</div>
  </div>

</div>

<div class="mt-10 flex flex-wrap justify-center gap-x-6 gap-y-2 text-sm">
  <a href="https://arxiv.org/abs/2309.13060" class="underline">arXiv 2309.13060</a>
  <a href="https://arxiv.org/abs/2603.24197" class="underline">arXiv 2603.24197</a>
  <a href="https://arxiv.org/abs/2410.03017" class="underline">arXiv 2410.03017</a>
  <a href="https://arxiv.org/abs/2506.08872" class="underline">arXiv 2506.08872</a>
  <a href="https://www.mdpi.com/2075-4698/15/1/6" class="underline">MDPI Societies 2025</a>
</div>

<!--
Using AI as a teacher will make Engineers sooo much better than Engineers that use it as an answer machine. 
Schools have already figured this out.

The key point: using it as an answer machine is worse than not using AI at all. So careful use is needed.

This goes back to "Focus on understanding". If they use AI to improve their understanding, then they basically have 
a teacher that is available for their questions 24/7.
-->

---
layout: image-left
image: /enthusiasm.jpg
class: flex flex-col justify-center
---

# Use their enthusiasm

Vibe code boring stuff with AI on side projects.

<!--
When you have a hobby project, there are certain parts you might enjoy, while you also need the boring stuff.
For example: creating the backend with Java could be fun, but Thymeleaf frontend is boring. Just let AI do the
boring stuff! It will make it far more enjoyable to create hobby projects this way.

Ask question: who hates doing frontend development? Hopefully a lot! 
-->

---
layout: center
class: text-center
---

# In summary

<div class="mt-10 mx-auto w-max flex flex-col gap-5 text-left">
  <div class="flex items-baseline gap-5">
    <span class="text-4xl font-bold w-10" style="color: var(--geist-foreground)">1</span>
    <span class="text-2xl">Focus on understanding</span>
  </div>
  <div class="flex items-baseline gap-5">
    <span class="text-4xl font-bold w-10" style="color: var(--geist-foreground)">2</span>
    <span class="text-2xl">Guide how to use AI</span>
  </div>
</div>

---
layout: cover
background: /end.jpg
class: text-center
---

# The end

<div class="mt-2 mx-auto w-max flex flex-col items-center gap-3">
  <div class="w-52 h-52 rounded-lg" style="background: url(/qr-code.png) center / contain no-repeat" role="img" aria-label="QR code linking to the slides"></div>
  <a href="https://github.com/ricoapon/slidev-guiding-engineers-ai" class="underline">github.com/ricoapon/slidev-guiding-engineers-ai</a>
</div>
