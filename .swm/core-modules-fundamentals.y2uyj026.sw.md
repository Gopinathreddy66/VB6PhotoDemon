---
title: Core Modules Fundamentals
---
# Core Modules Overview

Core Modules within the Modules directory are the foundational components that provide essential functionality for the photo editor. They are responsible for implementing critical operations that enable the application's core features.

# Key Responsibilities of Core Modules

These modules manage vital aspects such as user interface preferences and graphics processing. For example, they handle how users interact with the application and how images are rendered and manipulated.

# Interface Module

The Interface module specifically manages user preferences related to the layout and visibility of image tabs. This allows users to customize their workspace, improving usability and workflow efficiency.

# GDIPlus Module

The GDIPlus module encapsulates core functions for graphics rendering and image manipulation. It leverages the GDI+ graphics library to perform these tasks, forming the backbone of the photo editor's image processing capabilities.

# Purpose of Core Modules

Together, Core Modules implement the main features of the application, including multi-layer editing, color management, and user interface customization. These features are essential for delivering a robust and flexible photo editing experience.

# Using Core Modules in Development

Developers interact with Core Modules by invoking their functions to perform specific tasks. For instance, rendering images is handled through the GDIPlus module, while updating interface elements based on user preferences and image layer states is managed by the Interface module.

# Example Usage Scenario

Consider a scenario where a user customizes their workspace by adjusting the visibility of image tabs. The Interface module processes these preferences to update the UI accordingly. Simultaneously, when an image is edited, the GDIPlus module applies the necessary rendering and manipulation operations.

&nbsp;

*This is an auto-generated document by Swimm 🌊 and has not yet been verified by a human*

<SwmMeta version="3.0.0" repo-id="Z2l0aHViJTNBJTNBVkI2UGhvdG9EZW1vbiUzQSUzQUdvcGluYXRocmVkZHk2Ng==" repo-name="VB6PhotoDemon"><sup>Powered by [Swimm](https://app.swimm.io/)</sup></SwmMeta>
