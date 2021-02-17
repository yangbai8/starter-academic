---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 80

title: Projects
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
  - name: All
    tag: '*'
  - name: Deep Learning
    tag: Deep Learning
  - name: Other
    tag: Demo

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 2

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
**Project: Acoustic-based Sensing and Applications**
* Reviewed acoustic-based sensing in terms of hardware infrastructure, technical approaches, and its broad applications in recognition \& tracking, localization \& navigation, security \& privacy, and communication
* Discussed future research directions and limitations of the acoustic-based sensing

**Project: Inaudible High-throughput Acoustic Communication**
* Designed an acoustic communication system, which achieves high-throughput and inaudibility simultaneously, and the highest throughput we achieve is 12 times higher than the state-of-the-art acoustic communication systems
* Modeled the non-linearity of the mobile device’s inbuilt microphone and use Orthogonal Frequency Division Multiplexing (OFDM) technique together with the non-linearity model to transmit data bits over multiple orthogonal channels with an ultrasound frequency carrier
* Proposed an algorithm to eliminate the unrelated residual signals induced by Amplitude Modulation (AM)

**Project: Monitoring Movement Dynamics of Robot Cars and Drones**
* Proposed a smart system that can monitor the movement dynamics of carrying platforms (i.e., robot cars and drones) leveraging the inertial sensors of the attached smartphone
* Monitored the movement dynamics of carrying platforms in real time, such as moving speed, displacement, and position
* Achieved real-time movement dynamics sharing with the backend server through WiFi connection
