# Little Why

A voice-first prototype that helps parents and guardians explain abstract
concepts to children aged 2–6 who are blind or have low vision.

Built by Team 14 at the AI + Learning Differences Hackathon, Harvard
Graduate School of Education (November 2026).

**[Live demo](https://ronyastete.github.io/LittleWhy/)** · best in Chrome, allow microphone



https://github.com/user-attachments/assets/5ea6f29b-2b60-4273-97c5-f98d31e5817c



## The problem
Young children ask "why?" about things they usually learn by seeing, like
fire, clouds or shadows. Caregivers of visually impaired children need ways
to explain them through other senses.

## How it works
1. The guardian signs up and tells "Y", the guide, the child's name by voice.
2. They choose how the child likes to learn: sound, touch, smell, activity,
   spatial or kinesthetic.
3. When they ask a question, Y responds with three multi-sensory ways to
   explain it: an audio clip, a tactile craft, and a guided activity.
4. Every screen is read aloud, and every input can be spoken or typed.

## Prototype status
This is a hackathon demo of the intended experience. The conversation is
scripted around one example question ("What is fire?"), and accounts are
simulated; nothing is stored. A production version would generate the
suggestions with a language model, tailored to the child's preferences.

## Tech
Single-file HTML, CSS and vanilla JavaScript, with no build step or
dependencies. Web Speech API for speech recognition and text-to-speech,
with optional ElevenLabs or OpenAI voices.

## My role - Co-Designer
* Steered the team's ideation toward a single, clearly defined
  audience, guardians explaining to two to six-year-old
  children with visual impairments, which focused on
  the concept and the final product.
* Conducted background research on vision disabilities, from
  low vision to blindness, to ground the multi-sensory approach
  in evidence about how these children learn.
* Co-designed the app's interface and voice-first flow, and
  co-presented the project to a panel of disability experts.

## Team
- Stacey Cho - Co-designer
- Tamara Dzogovic - Co-designer
- Ling Fan - Co-designer
- Lindsay Kim - Co-designer
- Riya Parikh - Co-designer
- Jules Ramos - Co-designer
- Rony Astete - Co-designer

Original repository: https://github.com/Stacey628/LuckyCharmAgent

## Next steps
- Generate explanations for any question with an LLM
- Test with caregivers and vision specialists
- Screen-reader audit (ARIA labels, focus order)
- Dark Mode UI
