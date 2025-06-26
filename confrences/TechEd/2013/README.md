# TechEd 2013: Windows Phone 8 XAML Application Development  

This presentation, delivered by **Rudi Grobler** at **Microsoft TechEd Africa 2013**, provides a comprehensive guide to **XAML-based application development** for **Windows Phone 8**. The session covers the fundamentals of XAML, new features in Windows Phone 8, project infrastructure, key controls (e.g., `LongListSelector`, `Maps`), and performance optimizations. It also addresses compatibility with **Windows Phone 7** and highlights modern development practices like **async/await** and **Portable Class Libraries (PCL)**. Live demonstrations illustrate practical implementations, while the talk concludes with resources for further learning and community engagement.  

---

# Detailed Summary  

## **Introduction**  
- **Presenter**: Rudi Grobler ([rudigrobler.azurewebsites.net](http://rudigrobler.azurewebsites.net), Twitter: @rudigrobler).  
- **Event**: Microsoft TechEd Africa 2013 (Durban, 16–19 April).  
- **Focus**: XAML as the cornerstone of Windows Phone 8 app development.  

## **Agenda**  
1. **Overview**: XAML’s role in Windows Phone 8.  
2. **Building Windows Phone 8 Apps**: Infrastructure, controls, and .NET features.  
3. **Windows Phone 7 Compatibility**: Migration and shared APIs.  

---

## **Key Topics**  

### **1. XAML Fundamentals**  
- **Definition**: Declarative markup language for defining UI, aligned with Windows 8.  
- **Architecture**:  
  - **Windows Phone 8**: XAML + C#/VB atop Windows Phone Runtime.  
  - **Windows Phone 7**: Legacy XNA framework (for games) alongside XAML.  

### **2. Project Infrastructure & Design**  
- **Templates**: Updated for HTML5 and alignment grids.  
- **Localization**: Support for RTL (right-to-left) and bidirectional text.  
- **Multiple Resolutions**:  
  - **WVGA (480×800)**, **720p (720×1280)**, **WXGA (768×1280)**.  
  - Logical vs. physical pixels for scalable layouts.  
- **Demo**: Setting up a multi-resolution project with localized resources.  

### **3. Core Building Blocks**  
#### **Controls & Performance**  
- **Panorama/Pivot**: Reduced memory usage, smoother "first touch" experience.  
- **LongListSelector**:  
  - **Features**: Jump lists, grid views, sticky headers, infinite scrolling (`ItemRealized`).  
  - **Grouping**: Requires `IList<IList>` and `IsGroupingEnabled`.  
- **Maps**:  
  - Vector-based rendering, offline caching, fluid gestures (pinch/stretch).  
  - Overlay layers with off-thread updates.  
- **WebBrowser**: IE10 engine with HTML5, CSS3, and gesture support.  
- **ViewportControl**: Touch-optimized alternative to `ScrollViewer` (dynamic bounds, off-thread input).  

#### **Gestures**  
- **Pinch + Stretch**: Extended `ManipulationDeltaEventArgs` with `PinchManipulation` center points.  

### **4. .NET Enhancements**  
- **CoreCLR**: Optimized runtime.  
- **Async/Await**: Simplified asynchronous programming.  
- **HttpClient**: Modern HTTP requests.  
- **Portable Class Libraries (PCL)**: Code sharing across WP7, WP8, and Windows 8.  

### **5. Windows Phone 7 Compatibility**  
- **Backward Support**: Top apps and APIs remain functional.  
- **Tools**: Unified targeting for WP7.1 and WP8.0.  
- **Light-Up Strategy**: Use PCLs to share code while leveraging WP8-exclusive features.  
- **Demo**: Migrating a WP7 app to WP8.  

---

## **Summary & Takeaways**  
- **XAML is Central**: The primary UI framework for Windows Phone 8.  
- **Performance**: Critical improvements in controls (`Panorama`, `LongListSelector`) and rendering (Maps).  
- **Modern Practices**: Async/await, PCLs, and HttpClient streamline development.  
- **Compatibility**: WP7 apps can coexist with WP8, with pathways for gradual upgrades.  

## **Resources & Community**  
- **Related Sessions**:  
  - *Designing XAML Apps in Blend* (Wed 17:15).  
  - *Code Sharing Between WP8 & Windows 8* (Thu 17:15).  
- **Feedback**: Rate sessions via [MSDN South Africa](https://blogs.msdn.com/southafrica) or Twitter (@msdevsa).  

---

## **Final Notes**  
The presentation equips developers with actionable insights for building **scalable**, **performant**, and **cross-compatible** Windows Phone 8 applications. Emphasis on **XAML’s versatility** and **modern .NET tools** ensures apps align with Microsoft’s ecosystem while meeting user expectations for responsiveness and design.  

---

[Slides](slides.pdf)