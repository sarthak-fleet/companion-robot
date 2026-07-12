# PRD — Pace Companion Mode (V1)

## 1. Vision

Build an always-present AI companion that lives in the user's room using an old phone. Validate companionship before robotics.

---

## 2. Goal

Answer one question:

> **Does persistent presence create a better AI experience than opening an app?**

---

## 3. Target User

* Solo professionals
* Builders
* Students
* People working from home

---

## 4. Hardware

* Old iPhone
* Charging cable
* Phone stand/tripod
* Fixed corner placement

---

## 5. Core Features

* Always-on microphone
* Always-on camera
* Continuous conversation
* Long-term memory
* Room awareness
* Context continuity
* Voice output

---

## 6. Example Behaviors

* "Welcome back."
* "Your package arrived."
* "Where are my AirPods?"
* "You've been coding for 3 hours."
* "Remember yesterday's discussion?"

---

## 7. Perception

Detect:

* Person enters/leaves
* Voice
* Scene changes
* Objects
* User requests

---

## 8. Memory

Store:

* Conversations
* Room events
* Object locations
* User preferences
* Daily summaries

---

## 9. Personality

* Warm
* Curious
* Calm
* Doesn't interrupt unnecessarily
* Remembers previous conversations

---

## 10. Proactive Rules

Can:

* Welcome user
* Remind
* Warn
* Notice changes
* Continue conversations

Cannot:

* Constantly comment
* Guess emotions
* Interrupt frequently

---

## 11. Privacy

* Companion Mode explicit opt-in
* Visible camera indicator
* One-tap pause
* Local preprocessing
* User controls memory deletion

---

## 12. Technical Architecture

```
Camera + Mic
      ↓
Local Detection
      ↓
Backend Memory
      ↓
LLM
      ↓
Voice Response
```

---

## 13. MVP Scope

* Fixed camera
* Single room
* One user
* Voice conversations
* Vision Q&A
* Object memory
* Welcome back
* Basic reminders

---

## 14. Out of Scope

* Robotics
* Pan-tilt
* RC car
* Blimp
* Humanoid
* Multi-room support

---

## 15. Success Metrics

* Daily usage time
* Conversations/day
* Proactive interactions accepted
* "Where is X?" success rate
* User misses Companion Mode when disabled

---

## 16. Future Roadmap

**V2:** Pan-tilt camera

**V3:** Mobile body (RC car)

**V4:** Floating blimp companion

**V5:** Open robotics SDK

---

## Core Principle

> **Build the companion first. Upgrade the body later.**
