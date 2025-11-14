---
title: Basic Concepts of UI Core in Modules
---
# Overview of UI Core in Modules

UI Core represents the fundamental component responsible for managing the user interface within the application modules. It centralizes control over essential UI settings that influence the layout and user interaction experience.

Specifically, UI Core manages configurations such as the alignment and visibility of image tab strips, which are key elements in the application's interface. These settings ensure that the UI layout remains intuitive and consistent for users.

The management of these settings is integrated with user preferences, enabling the application to remember and restore UI configurations across sessions. This persistence enhances usability by maintaining a familiar interface state for users.

# Purpose and Role of UI Core

The primary purpose of UI Core is to provide a stable foundation for UI configurations and preferences. It acts as the base layer that supports more complex interface components and modules, ensuring consistent behavior and appearance.

By centralizing core UI management, UI Core facilitates modular development, allowing other modules to rely on its functionality for foundational UI tasks without duplicating code or logic.

# Using UI Core in Development

Developers interact with UI Core mainly through user preferences, accessing and modifying settings such as tab strip alignment and visibility. This approach allows the application to dynamically adapt the interface based on stored user choices.

For example, when a user adjusts the position or visibility of image tab strips, these preferences are saved via UI Core mechanisms. Upon subsequent application launches, UI Core applies these saved settings to restore the user's preferred layout.

# Example: Managing Image Tab Strips

A practical use case of UI Core is controlling the alignment and visibility of image tab strips within the editor. Through UI Core, these settings are stored in user preferences, ensuring that the interface reflects the user's customization consistently.

This mechanism not only improves user experience by preserving interface state but also simplifies the development process by encapsulating UI state management within a dedicated core module.

&nbsp;

*This is an auto-generated document by Swimm 🌊 and has not yet been verified by a human*

<SwmMeta version="3.0.0" repo-id="Z2l0aHViJTNBJTNBVkI2UGhvdG9EZW1vbiUzQSUzQUdvcGluYXRocmVkZHk2Ng==" repo-name="VB6PhotoDemon"><sup>Powered by [Swimm](https://app.swimm.io/)</sup></SwmMeta>
