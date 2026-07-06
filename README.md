# Rainmeter Skins

A collection of lightweight, customizable **Rainmeter skins** for Windows. This repository is intended to host useful desktop widgets and utilities that are easy to modify and reuse.

More skins will be added over time.

---

# Included Skin

## Interactive Timetable

A simple and customizable timetable widget for Rainmeter.

### Features

* 6-day × 6-period timetable layout
* Clean, minimal interface
* Native Rainmeter tooltips
* Lightweight (no external plugins required)
* Easy to customize for schools, colleges, universities, or work schedules

---

# Customization

The skin has been uploaded with **generic placeholder values** for privacy.

### 1. Change the title

Edit the **`[Title]`** meter:

```ini
Text=Course - Semester X
```

Example:

```ini
Text=B.Sc. Physics - Semester IV
```

---

### 2. Change the timetable

Each timetable cell has a section similar to:

```ini
[Cell22]
Text=ABCD
```

Replace `ABCD` with your course code or subject name.

Example:

```ini
Text=CS201
```

---

### 3. Edit tooltips

Every subject cell supports Rainmeter tooltips.

A sample tooltip is provided in **`ToolTip.txt`**.

Example:

```ini
ToolTipTitle=ABCD
ToolTipText=Faculty : Dr. ABCD#CRLF#Credits : 4
```

Copy this block into any subject cell and replace the placeholder values with your own information.

Rainmeter uses `#CRLF#` to create new lines inside the tooltip.

---

### 4. Change class timings

The time labels are defined in these sections:

```ini
[Time1]
[Time2]
...
[Time6]
```

Modify the `Text=` value to match your timetable.

---

### 5. Empty periods

Leave a cell empty by setting:

```ini
Text=
```

---

# Installation

1. Install Rainmeter.
2. Copy the skin folder into:

```
Documents\Rainmeter\Skins\
```

3. Refresh Rainmeter.
4. Load the skin from the Rainmeter Manager.

---

# Repository Roadmap

This repository will continue to grow with additional Rainmeter projects, including:

* Timetable widgets
* Productivity tools
* Desktop utilities
* System monitoring skins
* Experimental widgets

---

Feel free to modify, improve, and adapt these skins to suit your own workflow.
