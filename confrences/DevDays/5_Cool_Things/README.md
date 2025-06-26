# DevDays 2009: Five Cool Things to Know and Use for Smart Client Development  

This presentation, delivered by **Rudi Grobler** at **DevDays 2009**, highlights five key technologies for building **smart client applications** using **Visual Studio 2008** and the **.NET Framework 3.5**. The talk covers **WinForms-WPF interop**, the **Managed Extensibility Framework (MEF)**, **Client Application Services**, **ADO.NET Sync Services**, and **VSTO 3.0 for Office customization**. Each topic is demonstrated live, emphasizing practical applications for developers. The session concludes with a review of how these technologies enable resilient, extensible, and resource-efficient smart client applications.  

---

# Detailed Summary  

## **Introduction**  
- **Presenter**: Rudi Grobler ([dotnet.org.za/rudi](http://dotnet.org.za/rudi)).  
- **Focus**: Smart client development with VS 2008 and .NET 3.5.  

## **Agenda & Key Topics**  
### **1. WinForms and WPF Interop**  
- **Why Interop?**  
  - **WPF in WinForms**: Leverage existing WinForms code while adding WPF’s rich UI capabilities (e.g., `FlowDocument`).  
  - **WinForms in WPF**: Integrate legacy controls or features missing in WPF.  
- **Demo**: Live demonstration of hosting WPF controls within WinForms and vice versa.  

### **2. Managed Extensibility Framework (MEF)**  
- **Purpose**: Simplify application extensibility by enabling plug-in architectures.  
- **Key Benefit**: Dynamic composition of components without hard dependencies.  
- **Demo**: Showcasing MEF’s modular design for extensible applications.  

### **3. Client Application Services**  
- **Features**:  
  - **Authentication, Roles, and Profiles**: Centralized via ASP.NET application services.  
  - **Offline Support**: Cache credentials and roles for disconnected scenarios.  
- **Demo**: Configuring offline login and role-based access in a smart client.  

### **4. ADO.NET Sync Services**  
- **Problem Solved**: Network instability and offline data access.  
- **How It Works**:  
  - Syncs data between **local SQL Server Compact** and remote databases.  
  - Handles conflicts (e.g., updated/deleted rows) with incremental commands.  
- **Demo**: Synchronizing data bidirectionally with conflict resolution.  

### **5. VSTO 3.0 (Office Customization)**  
- **Capabilities**:  
  - **Ribbon Designer**: Customize Office 2007/2003 UIs.  
  - **Outlook Form Regions**: Extend Outlook with custom panes.  
  - **ClickOnce Deployment**: Simplified updates.  
- **Demo**: Building a Word content control or Outlook add-in.  

## **Core Tenets of Smart Clients**  
1. **Offline Capability**:  
   - Local data caching and background sync (via ADO.NET Sync Services).  
2. **Local Resource Utilization**:  
   - Leverage hardware (GPU, devices) and software (Office integration).  

## **Review & Summary**  
- **Key Takeaways**:  
  - **Interop Over Rewrite**: Bridge WinForms and WPF to modernize incrementally.  
  - **Embrace S+S (Software + Services)**: Combine local and cloud resources.  
  - **Build Ecosystems**: Use MEF for plug-ins, Sync Services for data resilience.  

## **Resources**  
- **Slides**: Available on Rudi’s blog ([dotnet.org.za/rudi](http://dotnet.org.za/rudi)).  
- **Microsoft Tools**:  
  - [MSDN](https://msdn.microsoft.com) for documentation.  
  - VSTO and Sync Services SDKs for implementation.  

---

### **Final Notes**  
The presentation underscores pragmatic approaches to smart client development, balancing legacy integration with modern capabilities. Developers are encouraged to adopt these technologies to create **resilient**, **extensible**, and **user-centric** applications.  

[Slides](slides.pdf)