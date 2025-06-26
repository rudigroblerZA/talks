# TechEd 2010 - "Using the MVVM Design Pattern with the Microsoft Visual Studio 2010 XAML Designer"

## Abstract

This presentation explores the application of the Model-View-ViewModel (MVVM) design pattern within the context of Microsoft Visual Studio 2010, emphasizing its benefits for building rich, maintainable, and testable user interfaces (UIs). The session provides an in-depth analysis of MVVM components—Model, ViewModel, and View—and illustrates how data binding, commanding, and separation of concerns facilitate a clean UI architecture. It discusses the differences between rich and poor models, highlights the importance of design tools like Visual Studio and Blend, and introduces the Basic XAML Framework (Bxf), a lightweight toolkit to streamline MVVM implementation across Silverlight, WPF, and Windows Phone 7. Practical demonstrations, resource links, and best practices guide developers in adopting MVVM effectively while minimizing reliance on code-behind and enhancing collaboration between designers and developers.

![DTL323](DTL323.PNG)

## Summary

- **MVVM Pattern Overview**:  
  - **Model**: Represents data, either as simple POCOs or rich domain objects supporting data binding.  
  - **ViewModel**: Acts as an intermediary, providing commands, properties, and logic to manipulate and present data, often extending or reshaping the Model.  
  - **View**: Presents UI elements, primarily using data binding and commanding, with minimal code-behind to enhance testability and separation of concerns.

- **Benefits of MVVM**:  
  - Improved testability of UI code  
  - Clear separation of UI and business logic  
  - Facilitates designer-developer collaboration  
  - Promotes disciplined UI architecture

- **Implementation Details**:  
  - Use of data binding and element binding within XAML to connect UI with ViewModel  
  - Resource generation in XAML for ViewModel instantiation  
  - Avoidance of heavy code-behind logic, favoring design-time data and ViewModel binding  
  - Introduction of the Basic XAML Framework (Bxf) for simplified MVVM setup

- **Practical Considerations**:  
  - Emphasis on the "plumbing" required for MVVM, such as routing View events to ViewModel commands  
  - View factory pattern to manage View creation and binding dynamically  
  - Strategies for managing data access and UI updates

- **Tools and Resources**:  
  - Visual Studio 2010 and Blend for designing and binding  
  - Bxf for lightweight MVVM components  
  - Links to further resources, community sessions, and training materials

- **Conclusion**:  
  - MVVM is a robust pattern for building testable, maintainable, and designer-friendly UIs  
  - Proper implementation requires understanding of data binding, commanding, and structured UI architecture  
  - Continuous learning and resource utilization are recommended for effective adoption

---

[Slides](DTL323_MVVM_VS2010_Grobler.pdf)