# Find_a_Route — Public Transit Scheduling & Route Finder App

Find_a_Route is a mobile app concept designed to simplify intercity public transit for everyday commuters. It maps real-time bus departures, route selections, platforms, and delay notifications for major transit pathways.

This repository details the platform's UI/UX wireframing principles alongside a Quality Assurance (QA) analytical test case and validation strategy.

## 🔗 Interactive Prototype Link
* [Click here to open the interactive Figma Prototype](https://www.figma.com/design/RFezndJvWlDbzol9kiLDtn/Find_a_Route?node-id=0-1&t=hcL6I8y5cnRavRhF-1)

---

## 🎨 Part 1: UI/UX & Interaction Design Highlights
* **Simplified Search Entry:** Optimized the departure-to-destination search flow using predictive address inputs and quick-toggle presets (Home, Work, More) to minimize interaction friction.
* **Real-Time Visual Cues:** Implemented prominent countdown displays and contrasting color indicators (e.g., orange banners highlighting specific travel delays) to maximize user accessibility on the go.
* **Commuter History Hub:** Structured a clear, visual tile system on the homepage displaying recent route cards (e.g., Colombo to Kandy, Matale, or Galle) for fast one-tap navigation.

---

## 🔍 Part 2: QA Testing Scenarios & Edge Cases
As a QA Analyst, the user interface was audited against the following core system edge cases and behavioral test scenarios:

* **Real-Time Data Discrepancies:** Analyzed display behaviors for asynchronous time updates—ensuring the "Next Departure" countdown panel dynamically handles data refresh cycles without causing visual stutter.
* **Negative & Boundary Testing (Search Fields):** Validated error-state parameters when entering invalid destinations, identical departure-to-destination locations, or special character inputs.
* **Component Constraint Analysis:** Checked layout behavior across varying mobile viewport resolutions to guarantee text wrapping for longer destination titles (e.g., Express intercity route labels) doesn't overlap or distort standard button touch zones.
* **Logical Flow Continuity:** Mapped the navigational state paths when clicking back icons to ensure the user retains prior search properties instead of losing input state.
