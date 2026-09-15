# 🌐 Part 0: Fundamentals of Web Apps

This section introduces the foundational principles of web development. We will examine how browsers interact with servers using an example application.

## 🛠 Developer Setup
Before writing code, we must set up our workspace. The browser's Developer Tools are our most valuable asset.

### The Golden Rule
**Always keep the Developer Console open.**

| Setting | Purpose |
| :--- | :--- |
| **Disable Cache** | Ensures you are always seeing the most recent version of the files, not old cached copies. |
| **Preserve Log** | Keeps logs visible even after the page reloads. |
| **Hide Extension URLs** | Filters out requests triggered by browser plugins, showing only your application's traffic. |

## 🚀 Workflow Diagram
Use this workflow every time you open a new web project for debugging:
```mermaid
graph TD
A[Open Browser] --> B[Open DevTools]
B --> C{Configure Network Tab}
C --> D[Disable Cache]
C --> E[Preserve Log]
D & E --> F[Reload Page & Analyze]
