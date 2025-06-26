# TechEd 2010 - "Best Practices: Building a Real-World Microsoft Silverlight Line-of-Business Application" (WUX407)

## Abstract

This session offers comprehensive best practices for developing robust, maintainable, and scalable Line-of-Business (LOB) applications using Microsoft Silverlight. Presented by Rudi Grobler, it emphasizes structured architectural patterns, particularly the Model-View-ViewModel (MVVM) pattern, to manage application complexity. The presentation covers essential topics such as consistent pattern adoption, effective data binding in nested controls, user notification mechanisms for success and failure, the use of service agents for clean service calls, and extending built-in controls to meet specific business needs. Through practical demonstrations and real-world insights, attendees learn how to implement these strategies to create professional-grade Silverlight applications that are easier to test, extend, and maintain.

![WUX407](WUX407.PNG)

## Summary

- **Introduction & Context**:
  - Developing real-world Silverlight LOB applications requires disciplined planning and architecture.
  - Challenges include managing numerous screens, validation, service integration, and data access.

- **Lesson #1: Adopt a Consistent Pattern**:
  - Essential to pick and stick to an architectural pattern like MVVM.
  - Helps prevent application complexity from spiraling out of control.
  - Common layers include validation, service calls, models, and data access.

- **Lesson #2: Data Binding & Nested Controls**:
  - Binding data in nested controls (e.g., DataGrid inside a ListBox) can be complex.
  - Techniques include using StaticResource binding and a DataContextProxy to manage scope and data context issues.
  - DataContextProxy simplifies nested UserControl data binding by exposing parent DataContext.

- **Lesson #3: User Notifications for Success & Failure**:
  - Use Silverlight’s animation and media capabilities to provide visual and auditory feedback.
  - Subtle animations and sounds can enhance user experience without intrusive message boxes.
  - Example: Animating status banners and playing sounds on operation success or failure.

- **Lesson #4: Service Agents for Service Calls**:
  - Encapsulate service calls in dedicated Service Agent classes for reusability and testability.
  - Service agents can implement interfaces to facilitate unit testing.
  - Example: Wrapping WCF service calls within a generic CallService method that manages proxies and event handlers.

- **Lesson #5: Extend Existing Controls**:
  - Instead of reinventing controls, extend built-in Silverlight and Toolkit controls to add specific functionality.
  - Examples include creating a FilteredTextBox, enhancing ComboBox for primary key handling, or extending AutoCompleteBox.
  - Extending controls improves reusability and maintains consistency.

- **Summary & Resources**:
  - Reinforces the importance of pattern consistency, effective data binding, user feedback, service encapsulation, and control extension.
  - Provides links to resources, community sessions, and further learning materials.
  - Encourages adopting these best practices for professional-grade Silverlight LOB applications.

---

[Slides](WUX407_Best_Practices_Grobler.pdf)