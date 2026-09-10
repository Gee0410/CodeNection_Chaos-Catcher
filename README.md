# 🌱 Chaos Catcher

### Don't just manage your tasks. Manage your capacity.

**A student workload and recovery manager designed to help university students understand their load, rebalance their priorities, and recover before overload builds up.**

---

## 📖 Project Overview

**Chaos Catcher** is a student-focused workload and recovery management application created for the **Lifestyle Track: Stress & Workload Manager** challenge.

University students often have to manage multiple responsibilities at the same time, including assignments, exams, part-time jobs, group projects, social commitments, errands, and their physical and mental wellbeing.

Instead of only helping students manage their tasks, Chaos Catcher focuses on helping them understand their **overall workload and current capacity**.

The system aims to help students:

* Understand how much they are carrying
* Identify which areas are creating the most pressure
* Prioritise and rebalance their responsibilities
* Take short recovery actions when needed
* Return to their tasks with a more manageable workload

> **Don't just manage your tasks. Manage your capacity.**

---

# 🚨 The Problem

University students are juggling many responsibilities at once.

Assignments, deadlines, part-time jobs, social commitments, errands, physical activities, and personal responsibilities can gradually pile up.

The problem is rarely one large task.

Instead, **multiple types of workload accumulate together without students clearly noticing how much they are carrying.**

Students may continue saying yes to new responsibilities, postpone tasks that feel less urgent, or keep working even when their available energy is already low.

### The Problem We Identified

Most productivity tools focus mainly on:

> **"What do I need to do?"**

However, students also need to understand:

> **"How much am I currently carrying?"**

and:

> **"What should I do when my capacity is low?"**

Chaos Catcher aims to bridge this gap by combining **workload awareness, capacity awareness, task rebalancing, and recovery actions** in one experience.

---

# 🎯 Target Users

Chaos Catcher is designed primarily for **university students** who are balancing academic responsibilities with other areas of daily life.

### Our target users include:

* Undergraduate students
* Students managing multiple assignments and deadlines
* Students with part-time jobs
* Students involved in group projects
* Students balancing academic and personal responsibilities
* Students who need a simpler way to understand and manage their overall workload

### Example User Situation

A student may have:

```text
📚 2 assignments due tomorrow
👥 Group meeting tonight
🏫 Classes throughout the day
🧺 Several errands
😴 Limited sleep
```

Each responsibility may seem manageable on its own.

However, when combined, the student's overall workload may become too high.

Chaos Catcher aims to make this combined load more visible.

---

# 💡 Our Approach

Chaos Catcher is built around three connected concepts:

```text
┌─────────────────┐
│    WORKLOAD     │
│ What am I       │
│ carrying?       │
└────────┬────────┘
         ↓
┌─────────────────┐
│    CAPACITY     │
│ How much can I  │
│ realistically   │
│ handle?         │
└────────┬────────┘
         ↓
┌─────────────────┐
│    RECOVERY     │
│ What can I do   │
│ to reset?       │
└─────────────────┘
```

Instead of simply tracking tasks, the system aims to connect:

> **Understand → Rebalance → Recover → Continue**

---

# 📊 Five-Dimension Workload Model

Chaos Catcher represents student workload across five dimensions mentioned in the problem statement.

| Dimension       | What it represents                       | Examples                              |
| --------------- | ---------------------------------------- | ------------------------------------- |
| 🧠 **Mental**   | Cognitive effort and mental workload     | Studying, coding, writing             |
| ⏰ **Time**      | Deadline and schedule pressure           | Multiple deadlines, packed schedules  |
| 🏃 **Physical** | Physical demands and fatigue             | Walking, activities, commuting        |
| 👥 **Social**   | Social responsibilities and interactions | Group meetings, social commitments    |
| 🧺 **Errands**  | Daily-life responsibilities              | Laundry, shopping, collecting parcels |

### Why these five dimensions?

A student's workload is not only academic.

For example, a student may have only two assignments but also have several group meetings, errands, a part-time shift, and insufficient recovery.

Therefore, Chaos Catcher aims to provide a broader picture of the student's **combined workload**.

---

# ✨ Core Features

Chaos Catcher combines **workload awareness, capacity-based planning, task rebalancing, and recovery** into one student-focused experience.

Rather than simply showing users what they need to complete, the system helps them understand **what they can realistically handle right now**.

---

## 1. 🏠 Dashboard & Smart Triage

The dashboard acts as the user's main **action and triage hub**, presenting only the information that matters most at the current moment.

### Key Features

* **Today's Focus** — Restricts the daily view to the most critical 1–2 tasks to reduce decision fatigue.
* **Voice Brain Dump** — Users can speak their thoughts naturally instead of manually creating multiple tasks. AI converts the input into structured and categorised tasks.
* **Smart Intervention** — When workload exceeds the user's capacity, the system identifies suitable non-urgent tasks for postponement.

### Example

Instead of showing:

```text
8 Tasks
5 Deadlines
3 Errands
2 Group Meetings
```

Chaos Catcher focuses the user on:

```text
TODAY'S FOCUS

① Complete Database Assignment
② Prepare Group Presentation

Everything else can wait.
```

---

# 2. 🧠 Capacity-Aware Task Management

Chaos Catcher does not treat every task equally.

Tasks are evaluated according to their **effort, urgency, workload dimension, and the user's personal capacity**.

### Five Capacity Dimensions

* 🧠 Mental
* ⏰ Time
* 🏃 Physical
* 👥 Social
* 🧺 Errands

Users can define their personal capacity baselines through **Capacity Sliders**.

This allows the system to understand that two students may have the same number of tasks but very different levels of available capacity.

---

## 3. 🗺️ Predictive Load Calendar

The **Load Calendar** provides a forward-looking view of workload rather than only showing today's tasks.

Instead of displaying only:

> Monday → Tuesday → Wednesday

the calendar highlights **future workload density and potential bottlenecks**.

### Example

```text
MON      TUE       WED       THU       FRI

🟢       🟡        🔴        🔴        🟢
                   ↑         ↑
              4 deadlines approaching
```

The system can identify upcoming high-load periods and encourage students to start earlier before workload accumulates.

---

# 4. 🔄 Smart Reshuffle & "I'm Fried" Mode

This is one of the core concepts of Chaos Catcher.

When the user's workload exceeds their current capacity, the system can propose a **lighter version of the day**.

### One-Click Reshuffle

Instead of simply warning:

> "Your workload is high."

Chaos Catcher proposes specific changes.

```text
Current Load

82% ━━━━━━━━━━━━━━━━

Suggested Plan

✓ Keep: Database Assignment
✓ Keep: Group Meeting
→ Move: Laundry → Tomorrow
→ Shorten: Revision → 30 min

New Load

64% ━━━━━━━━━━━━━
```

Users can review and accept the proposed changes with one action.

---

## 🔋 "I'm Fried" Mode

When users feel completely overwhelmed, they can activate **I'm Fried** mode.

The system simplifies the interface by:

* Hiding heavy or non-essential tasks
* Showing only immediate priorities
* Suggesting small, manageable actions
* Surfacing recovery activities

The goal is to reduce the feeling of:

> **"I have too much to do."**

and replace it with:

> **"Just focus on this for now."**

---

# 5. ⏱️ Adaptive Focus & Cognitive Protection

Chaos Catcher supports focused work without forcing users into a rigid productivity pattern.

### Adaptive Focus Timer

Instead of always using a fixed 25-minute Pomodoro cycle, the timer can adapt the focus session according to the user's current state.

For example:

```text
Normal Capacity
25 min Focus
       ↓
5 min Break

Lower Capacity
15 min Focus
       ↓
5 min Break
```

The purpose is to make productivity more **capacity-aware**, rather than simply encouraging users to work for longer.

---

# 6. 🌿 Guided Recovery

Recovery is an integrated part of Chaos Catcher's workload management loop rather than a separate wellness section.

When users need to step away, they can choose from short recovery activities.

### Recovery Activities

#### 🌬️ Breathing Reset

A guided 1-minute breathing activity using a simple expanding and contracting visual.

```text
Breathe In
    ↓
Hold
    ↓
Breathe Out
```

#### 🚶 Mindful Walk

A short timer encouraging users to step away from their screen and take a brief walk.

#### 🧘 Stretch & Posture

Short desk-friendly routines such as:

* Desk Reset
* Neck & Shoulder Relief
* Spine Stretch

#### 🎧 Disconnect

Ambient soundscapes such as:

* Ocean Waves
* Forest Rain
* Nature Sounds

Users can also create a personalised recovery sequence through the **Active Reset Builder**.

---

# 7. 📈 Recovery & Workload Monitor

Chaos Catcher helps users understand the relationship between their workload and recovery over time.

Instead of relying only on traditional charts, the Monitor uses **narrative data storytelling** to explain patterns in a more human-readable way.

### Example

> **Your mental workload was higher this week.**
> Most of the increase came from your database assignment and multiple upcoming deadlines.

The Monitor can also compare:

```text
WORKLOAD
████████████████░░  82%

RECOVERY
████████░░░░░░░░░░  40%
```

This helps users recognise when they are carrying a high workload without enough recovery.

---

# 🔁 The Chaos Catcher Core Loop

All of these features are connected through one continuous workflow:

```text
        DETECT
          ↓
     Understand
      Workload
          ↓
       CHECK
      Capacity
          ↓
      REBALANCE
          ↓
        ACT
          ↓
      RECOVER
          ↓
     SMART RETURN
          ↓
       MONITOR
          ↓
      IMPROVE
```

The key difference is that Chaos Catcher does not stop at **task tracking**.

It connects:

> **What I have → What I can handle → What I should do → When I should recover**

---

# 🔁 Core User Flow

The current concept follows this general flow:

```text
Onboarding
    ↓
Dashboard
    ↓
Add / Capture Tasks
    ↓
Understand Workload
    ↓
Check Capacity
    ↓
High Workload?
   /       \
 No         Yes
 ↓           ↓
Continue   Rebalance
             ↓
          Recovery
             ↓
       Mental Check-in
             ↓
        Smart Return
             ↓
           Monitor
             ↓
          Continue
```

---

# 🚀 Next Steps

The next development stages will focus on:

* Completing the mobile prototype
* Refining the workload visualisation
* Finalising the task rebalancing experience
* Connecting recovery with workload management
* Testing the user flow
* Exploring technical implementation

More advanced ideas explored during ideation will be evaluated based on technical feasibility and development scope.

---

# 🔗 Project Resources

### 🎨 Figma Prototype

**[Coming Soon]**

### 📊 Presentation Slides

**[Coming Soon]**

### 🎥 Demo Video

**[Coming Soon]**

---

# 🌱 Our Vision

Students do not always need to become more productive.

Sometimes, they need to understand **what they can realistically carry**.

Chaos Catcher aims to help students:

> **See the load.
> Understand their capacity.
> Rebalance what they carry.
> Recover when needed.
> Return with less chaos.**

---

### Chaos Catcher

**Don't just manage your tasks. Manage your capacity.**
