# NestLink – Ambient Elderly Monitoring System

## Overview
NestLink is a discreet, non-intrusive monitoring system designed to support elderly wellbeing while preserving independence and dignity. It replaces wearables and cameras with intelligent, sensor-enabled everyday objects that passively collect behavioral and physiological data.

The system communicates insights through an ambient, screenless receiver using light patterns and alerts—ensuring continuous awareness without disruption.

---

## Core Philosophy

- **Invisible Monitoring**  
  No active interaction required from the elderly user.

- **Preserved Dignity**  
  No cameras, no invasive tracking interfaces.

- **Ambient Awareness**  
  Information delivered through subtle visual cues instead of dashboards.

- **Priority-Based Alerts**  
  Critical health events override all other system signals.

---

## System Architecture

NestLink consists of distributed sensor nodes embedded in household objects, connected to a central receiver.

### Components

#### 1. Smart Cup (Biometric Sensor Node)

A daily-use drinking cup with embedded biometric sensing.

**Functionality:**
- Captures heart rate and stress indicators via touch
- Uses capacitive or optical sensing
- Periodically transmits data to the receiver

**Design Intent:**
- Integrates into natural hydration habits
- Enables passive physiological monitoring

**Key Value:**
- Provides meaningful health snapshots without wearables

---

#### 2. Smart Door Knob (Activity Sensor Node)

A standard door knob enhanced with interaction sensing.

**Functionality:**
- Detects door usage events
- Logs activity frequency and timing
- Sends event-based updates

**Design Intent:**
- Zero learning curve
- Seamless environmental integration

**Key Value:**
- Infers movement patterns and detects inactivity anomalies

---

#### 3. Ambient Sound Artifact (Safety Sensor Node)

A decorative object with embedded acoustic monitoring.

**Functionality:**
- Detects loud or abnormal sounds (e.g., falls)
- Recognizes distress keywords (e.g., "help")
- Triggers alerts only on threshold events

**Design Intent:**
- Blends aesthetically into living spaces
- No visible surveillance cues

**Key Value:**
- Enables emergency detection without cameras

**Privacy Consideration:**
- Prefer on-device processing
- Avoid continuous cloud-based listening

---

#### 4. Central Receiver (Ambient Feedback Hub)

A screenless device that aggregates and communicates system state.

**Functionality:**
- Receives sensor data via internet connectivity
- Interprets and prioritizes signals
- Displays status using light and sound

**Design Principles:**
- No screens (low cognitive load)
- Light-based interaction language
- Glanceable and emotionally neutral

---

## Interaction Model

### System States

#### 1. Ideal State (Baseline Monitoring)
- **Visual:** Orange → Yellow gradient glow
- **Meaning:** Normal conditions
- **Behavior:** Calm, steady illumination

---

#### 2. Heart Rate Monitoring (Highest Priority)
- **Visual:** Warm pulsing light
- **Meaning:** Active biometric sensing

**Critical Condition:**
- **Trigger:** Abnormal heart rate
- **Visual:** Red pulsing light
- **Audio:** Buzzer alert
- **Priority:** Overrides all other states

---

#### 3. Door Activity (Routine Movement)
- **Visual:** Green-blue animated motion
- **Meaning:** Door interaction detected
- **Behavior:** Directional movement pattern

---

#### 4. Sound Alert (Emergency Event)
- **Trigger:** Loud noise or distress keyword
- **Visual:** Flashing/intensified light
- **Audio:** Immediate buzzer

---

## Priority Logic

1. Critical health alerts (heart rate extremes)
2. Emergency sound detection
3. Routine activity signals (door usage)
4. Idle ambient state

---

## Key Benefits

### For Elderly Users
- No wearable devices required
- No behavioral changes needed
- Maintains privacy and independence

### For Caregivers / Family
- Passive reassurance
- Immediate alerts for emergencies
- Reduced need for constant check-ins

---

## Design Strengths

- High adoption due to familiar object integration
- Minimal cognitive and physical burden
- Non-intrusive, emotionally neutral feedback system

---

## Risks & Considerations

### 1. Data Accuracy
- Intermittent heart rate readings
- Grip-based sensing variability

### 2. False Positives / Negatives
- Sound misclassification
- Activity ≠ actual wellbeing

### 3. Privacy Concerns
- Acoustic monitoring sensitivity
- Need for transparent communication and local processing

### 4. Interpretation Gap
- Light-based feedback may be insufficient remotely
- Requires optional digital interface for caregivers

---

## Potential Extensions

- Companion mobile application for detailed insights
- AI-based anomaly detection and behavior modeling
- Integration with emergency services
- Additional sensor nodes (bed, chair, etc.)

---

## Summary

NestLink transforms everyday household objects into an intelligent care network. By combining passive sensing with ambient feedback, it creates a balance between safety and autonomy—enabling elderly individuals to age in place with dignity while keeping caregivers informed.