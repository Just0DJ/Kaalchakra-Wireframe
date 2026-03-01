# 📄 Product Requirements Document (PRD)
## Kaalchakra – Tamil Cultural Calendar App

---

## 1. Product Overview

**Product Name:** Kaalchakra  
**Platform:** Android  
**Design Philosophy:** Modern UX × Tamil cultural continuity  
**Stage:** Concept & Low-Fidelity Design

**Kaalchakra** is a modern Android calendar application designed to help future generations of Tamilians stay connected with traditional cultural practices in a calm, respectful, and non-preachy manner.

The app focuses on **daily relevance**, **clarity**, and **emotional connection**, rather than rigid rule enforcement.

---

## 2. Problem Statement

Tamil Hindu culture involves many time-based practices such as:
- Food observances (veg / non-veg days)
- Vrathams and fasting
- Festival awareness
- Auspicious and inauspicious timings
- Bathing and ritual practices

### Current Issues:
- Information is fragmented across elders, WhatsApp messages, and physical calendars
- Existing apps are often:
  - Visually cluttered
  - Outdated in UX
  - Overly religious or prescriptive
- Younger users struggle to relate or stay consistent

---

## 3. Solution Overview

Kaalchakra provides:
- A **daily-first experience** (Today Screen)
- Clear Tamil + English date information
- Context-aware cultural guidance
- Gentle reminders instead of commands
- A modern Material-style interface

The app is designed to feel like a **cultural companion**, not an instruction manual.

---

## 4. Target Users

### Primary Users
- Tamil Hindu families
- College students living away from home
- Working professionals
- Users trying to reconnect with cultural routines

### Secondary Users
- NRIs
- Non-native Tamilians learning about culture
- Younger generations unfamiliar with traditions

---

## 5. Core Features (MVP)

### 5.1 Home / Today Screen

Displays:
- English Date
- Tamil Date
- Tamil Day
- Nakshatram / Thithi (future scope)

Sections:
- Daily Tamil Wisdom
- Today’s Observances
- Do’s & Don’ts cards
- Bottom navigation

---

### 5.2 Daily Tamil Wisdom

**Purpose:**  
To gently pass Tamil ethical and cultural wisdom to future generations.

**Content Sources:**
- Thirukkural
- Classical Tamil prose
- Cultural sayings
- Contextual wisdom (festival-linked)

**Behavior:**
- One quote per day
- Rotates automatically
- Offline-first
- Optional English meaning toggle

**Tone:**
- Reflective
- Calm
- Non-preachy

---

### 5.3 Monthly Calendar View

- English + Tamil month display
- Monthly grid layout
- Visual indicators for:
  - Festivals
  - Vrathams
  - Observances
- Tap a date to view details

---

### 5.4 Day Detail Screen

Displays:
- Selected date (English + Tamil)
- Events / festivals
- Cultural practices
- Auspicious or inauspicious notes

Actions:
- Set reminder
- View explanation (future)

---

### 5.5 Festivals & Events List

- Searchable list
- Filter by month or type
- Each item shows:
  - Festival name
  - Tamil date
  - Category (Festival / Vratham / Observance)

---

### 5.6 Settings

User controls:
- Language toggle (Tamil / English)
- Notification preferences
- Practice preferences:
  - Food observances
  - Bathing practices
  - Vratham reminders
- About section

---

## 6. UX & Design Guidelines

- Low cognitive load
- Material Design spacing
- Cards-based layout
- Dark mode support
- Accessibility-friendly typography

**Tone guideline:**  
> “Inform, don’t instruct.”

---

## 7. Data & Logic

### Data Requirements
- Tamil calendar dataset
- Festival & observance database
- Quote database for Daily Tamil Wisdom

### Logic Example

If today == Amavasai:
Show restraint-related observance
Display reflective wisdom quote

---

## 8. Technical Direction (Planned)

- Language: Kotlin
- UI: Jetpack Compose
- Architecture: MVVM
- Storage: Room (offline-first)
- Notifications: WorkManager

---

## 9. Non-Functional Requirements

- Offline usability
- Fast app launch
- Lightweight APK
- No ads in MVP
- Privacy-respecting (minimal permissions)

---

## 10. Future Enhancements

- Home screen widgets
- Audio playback for wisdom quotes
- Panchangam explanations
- AI-assisted modern Tamil reflections
- iOS version
- Region-specific observances

---

## 11. Success Metrics

- Daily active users
- Reminder opt-in rate
- 30-day retention
- User feedback quality

---

## 12. Risks & Considerations

- Calendar accuracy
- Cultural sensitivity
- Avoiding religious bias
- Content validation

---

## 13. Closing Note

Kaalchakra is not designed to **teach culture**,  
but to **keep culture alive through daily presence**.

This document represents the foundational thinking behind the product.
