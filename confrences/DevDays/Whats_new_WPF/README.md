# DevDays 2010: What’s New in WPF and Smart Clients in .NET 4.0  

This presentation, delivered by **Rudi Grobler** at an unspecified event, explores the advancements in **Windows Presentation Foundation (WPF)** and **Smart Clients** introduced with **.NET Framework 4.0**. The talk highlights key improvements such as **multi-touch support**, **Windows 7 taskbar integration**, **graphics and text rendering enhancements**, **ClickOnce deployment upgrades**, and **new controls**. Additionally, it covers foundational updates like **cached compositions**, **layout rounding**, and **accessibility improvements**. The session concludes with demonstrations, developer resources, and opportunities for further engagement with Microsoft’s developer community.  

---  

# Detailed Summary  

## **Introduction**  
- **Presenter**: Rudi Grobler (Barone, Budge & Dominick).  
- **Contact**: [Blog](http://www.rudigrobler.net), Twitter (@rudigrobler), Email (rudi@bbd.co.za).  

## **Key Highlights of WPF 4.0**  
### **1. Light Up Windows 7**  
- **Taskbar Integration**: Support for jump lists, progress bars, and icon overlays.  
- **Multi-Touch Enhancements**:  
  - New manipulation events (e.g., double-tap, rollover).  
  - Raw touch input for low-level control.  
  - Updated controls (`ScrollViewer`, `ScatterView`) for touch responsiveness.  
  - Compatibility with **Microsoft Surface SDK 2.0**.  

### **2. Fundamentals**  
- **Framework Deployment**:  
  - **.NET 4 Client Profile** (26MB) for lightweight installations.  
  - Brandable deployment experience (customizable installers).  
- **Application Deployment**:  
  - **ClickOnce Improvements**:  
    - Command-line arguments.  
    - File associations.  
    - Background updates.  
- **Graphics & Performance**:  
  - **Cached Composition**: Optimizes rendering via `UIElement.CacheMode` and `BitmapCacheBrush`.  
  - **Animation Easing Functions**: Customizable animation curves (e.g., bounce effects).  
  - **Pixel Shader 3.0**: Advanced GPU effects (no software fallback).  

### **3. Text & Layout Improvements**  
- **New Text Rendering Stack**:  
  - Sharper text (especially for East-Asian fonts).  
  - Options for aliased, grayscale, or ClearType rendering.  
- **Layout Rounding**: Ensures crisp UI by snapping elements to whole pixels.  

### **4. New Controls & Features**  
- **Data Controls**: `DataGrid`, `DatePicker`, `Calendar`.  
- **Visual State Manager (VSM)**: Now integrated into WPF.  
- **Dynamic Object Support**: Data binding with `IDynamicMetaObjectProvider`.  

### **5. Accessibility & Bug Fixes**  
- Support for **UIAccessible2**.  
- Hundreds of bug fixes and stability improvements.  

## **Demonstrations**  
- **Multi-Touch**: Implementing touch interactions in 20 lines of code.  
- **Cached Composition**: Optimizing vector rendering.  
- **Animation Easing**: Customizing motion effects.  
- **Text Clarity**: Comparing WPF 4.0 vs. GDI rendering.  

## **Resources & Community**  
- **MSDN**: [msdn.com](http://msdn.com).  
- **Training**: [microsoft.com/learning](http://microsoft.com/learning).  
- **Slides**: Available on [Rudi’s blog](http://www.rudigrobler.net/speaking).  
- **Engagement**: Connect via [MS Dev SA](https://blogs.msdn.com/southafrica) or Twitter (@msdevsa).  

## **Conclusion**  
The presentation underscores Microsoft’s commitment to enhancing WPF for modern desktop applications, emphasizing performance, usability, and developer productivity. Attendees were encouraged to explore the new features and provide feedback to shape future updates.  


[Slides](slides.pdf)