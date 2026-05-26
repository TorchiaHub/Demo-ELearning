# Block Architecture

MyLearn Enbital is organized around reusable course blocks. A block is not just a slide: it defines what the learner sees, what the phone does, what the avatar explains and what event should be tracked.

## Block Types

| Block type | Purpose | Example in the demo |
|---|---|---|
| Hook | Introduce the module and set the learning frame | Welcome and course setup |
| Pairing | Connect the mobile companion | QR code and companion code |
| Content | Explain a safety concept | Roles, machine safety, reporting culture, PPE |
| Interaction | Ask the learner to act | Hotspot selection, quiz, ordering, scenario decision |
| Social reveal | Compare responses in a controlled demo view | Group perception of risk |
| Acknowledgement | Confirm a demo-only learning step | Training recap confirmation |
| Summary | Close the learning path | Key takeaways and learning portrait |
| Final quiz | Evaluate understanding | End-of-module test |

## Why Blocks Matter

The block model makes the course easier to reason about:

- each step has a clear educational goal;
- desktop, phone and avatar can stay synchronized;
- interactions can be reused across different lessons;
- tracking can be attached to meaningful learning events instead of generic page views;
- the experience can evolve from a demo into a larger course catalogue.

## Dual-Device Pattern

The desktop and phone have different responsibilities.

| Surface | Role |
|---|---|
| Desktop | Avatar, lesson content, scenarios, maps, live feedback and debrief |
| Phone | Answering, selecting, confirming, classifying and advancing |
| Event log | Demo trace of important actions and course progress |

This split makes the phone feel like part of the training experience instead of a second screen that simply duplicates the desktop.

## Demo Course Sequence

| # | Block | Experience |
|---|---|---|
| 1 | Welcome | Elena introduces the module and the dual-device experience |
| 2 | Mobile connection | The learner pairs the phone to the desktop session |
| 3 | Safety roles | Concept map about workplace-safety responsibilities |
| 4 | Identify critical signals | Hotspot selection from the phone |
| 5 | Who should you report to? | Multiple-choice safety question |
| 6 | Machine stopped does not mean safe | Lesson about residual risk and isolation |
| 7 | Machine-safety sequence | Procedure ordering exercise |
| 8 | Critical decision | Scenario-based choice with consequence |
| 9 | Reporting culture | Lesson about near misses and prevention |
| 10 | Technical true/false | Fast safety check from mobile |
| 11 | Personal protective equipment | Lesson about PPE in the prevention hierarchy |
| 12 | Risk traffic light | Risk-level classification exercise |
| 13 | Group comparison | Demo social reveal of risk perception |
| 14 | Demo acknowledgement | Non-legal training acknowledgement |
| 15 | Summary | Recap of concepts and learning portrait |
| 16 | Final quiz | End-of-module knowledge check |

## Compliance Boundary

The demo separates learning completion, gamification, acknowledgement, quiz results and certification. The acknowledgement step is intentionally described as demo-only: it is not a digital signature and does not generate a legal certificate.

