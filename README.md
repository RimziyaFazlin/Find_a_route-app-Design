# Find_a_Route — Public Transit Scheduling & Route Finder App

Find_a_Route is a mobile app concept designed to simplify intercity public transit for everyday commuters by mapping out route selections, arrival schedules, and delay notifications.

This repository contains the interactive UI/UX prototype alongside the logical Quality Assurance (QA) test scenarios mapped out for the system.y.

## 🔗 Interactive Prototype Link
* [Click here to open the interactive Figma Prototype](https://www.figma.com/design/RFezndJvWlDbzol9kiLDtn/Find_a_Route?node-id=0-1&t=hcL6I8y5cnRavRhF-1)

### 🎨 Part 1: UI/UX & Interaction Design Layout
*   **Search Interface:** Designed a straightforward departure-to-destination search flow featuring quick-toggle presets (Home, Work, More) for rapid inputs.
*   **Visual Status Indicators:** Included distinct countdown elements and high-contrast alert banners (such as orange notices for bus delays) to ensure key updates are instantly readable.
*   **Recent Routes Layout:** Structured a clean tile system on the homepage displaying recently traveled pathways (e.g., Colombo to Kandy, Matale, or Galle) for fast navigation.

### 🔍 Part 2: QA Test Scenarios & Logic Verification
The interface layout was evaluated against the following functional logic and test scenarios:
*   **Dynamic Data Layout Scenarios:** Mapped out test logic for how the UI handles real-time visual updates, checking screen space constraints when active countdown banners or delay alerts appear.
*   **Text & Component Constraints:** Audited the visual boundaries to ensure longer intercity destination names wrap cleanly without distorting buttons, overlapping icons, or breaking alignment.
*   **Navigation Path Consistency:** Verified transition pathways across the three core views, ensuring back buttons properly return users to their previous search states without losing flow history.
