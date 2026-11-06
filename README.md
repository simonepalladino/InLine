# ⚽ inLine — Your Football Buddy

[![Apple Foundation Program](https://img.shields.io/badge/Program-Apple%20Foundation%20Program-black.svg)](https://developer.apple.com/)
[![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20watchOS-lightgrey.svg)](https://apple.com)
[![ML](https://img.shields.io/badge/ML-CoreML%20%7C%20Roboflow-orange.svg)](https://developer.apple.com/documentation/coreml)

**inLine** is an IoT and Machine Learning assistant designed for amateur football to introduce affordable Goal Line Technology using consumer Apple devices. By combining computer vision on the iPhone with real-time feedback on the Apple Watch, **inLine** helps referees make accurate goal-line decisions, reducing disputes and keeping the focus on friendship and fair play.

Developed between May 2023 and July 2023 as part of the **Apple Foundation Program**

---

## 🎯 Purpose & Goal

In amateur football, controversial refereeing decisions often lead to heated disputes among players. **inLine** leverages mobile technology to assist—not replace—the referee by detecting whether the ball has crossed the goal line.

* **Promote Fair Play**: Enhance the amateur football experience and maintain friendship on the pitch.
* **Smart Referee Assistant**: Provide real-time technological support directly to the referee's wrist.
* **Accessible Technology**: Utilize existing consumer hardware (iPhone & Apple Watch) instead of costly professional VAR infrastructure.

---

## 📱 How It Works

The application operates across two synchronized Apple devices:

1. **iPhone (Goal-Line Detector)**:
   * Placed at the height of the crossbar facing the goal line.
   * Uses real-time camera input and an object detection model to recognize when the ball enters the goal.
2. **Apple Watch (Referee Control)**:
   * Worn by the match referee on the pitch.
   * Receives real-time alerts when a potential goal occurs.
   * Allows the referee to validate or reject the goal during match action.
   * Features built-in match management tools (timer, score tracker).

---

## 🧠 Machine Learning & Tech Stack

* **CoreML**: On-device machine learning framework used for real-time football detection.
* **Roboflow**: AI-assisted tool used for bounding-box labeling, instance segmentation, and dataset management.
* **Dataset**: Custom-built training dataset featuring 550 labeled football photos to ensure reliable detection.

---

## 🛠 Features

* **Real-Time Ball Recognition**: High-confidence object detection tailored for footballs.
* **Instant Alerts**: Audio and haptic notifications sent directly to the referee.
* **Guided Setup**: Interactive tutorial/help section with step-by-step camera and guideline setup instructions.
* **Match Management**: Integrated watchOS interface for timing and scorekeeping.

---

## 🔮 Future Roadmap

* **Multi-Goal Server Architecture**: Centralized server integration to connect multiple iPhones simultaneously, providing goal-line monitoring across both pitch goals synced to a single Apple Watch.

---
