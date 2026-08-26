# ScheduledTasks

VS 2012 C# wrapper for Windows Task Scheduler 1.0 and 2.0 (CodePlex TaskScheduler by David Hall). `Microsoft.Win32.TaskScheduler` (.NET 2.0 library, assembly company CodePlex Community) wraps V1 and V2 COM as `TaskService`, `Task`, `TaskFolder`, `Trigger`, and `Action`, with fluent `Execute` helpers and `Trigger.FromCronFormat`. `TaskEditor` (.NET 3.5 UI library) adds localizable WinForms editors (AeroWizard, GroupControls, TimeSpan2); the solution also includes SecurityEditor, COMTask (`ITaskHandler` sample), TaskServiceExecutor, and C#/VB.NET test hosts. Open `TaskService.sln` in Visual Studio; this tree is a working copy of third-party source kept in Dave Robinson's Historical Dev archive.

**Source last updated:** 2013-08-14  
**Language:** C#, VB.NET  
**Target:** v2.0, v3.5  
**Output:** Library, WinExe

## What it is

VS 2012 C# wrapper for Windows Task Scheduler 1.0 and 2.0 (CodePlex TaskScheduler by David Hall). `Microsoft.Win32.TaskScheduler` (.NET 2.0 library, assembly company CodePlex Community) wraps V1 and V2 COM as `TaskService`, `Task`, `TaskFolder`, `Trigger`, and `Action`, with fluent `Execute` helpers and `Trigger.FromCronFormat`. `TaskEditor` (.NET 3.5 UI library) adds localizable WinForms editors (AeroWizard, GroupControls, TimeSpan2); the solution also includes SecurityEditor, COMTask (`ITaskHandler` sample), TaskServiceExecutor, and C#/VB.NET test hosts. Open `TaskService.sln` in Visual Studio; this tree is a working copy of third-party source kept in Dave Robinson's Historical Dev archive.

## Solution structure

| Project | Language | Path |
|---------|----------|------|
| `TaskService` | C# | `TaskService.csproj` |
| `COMTask` | C# | `COMTask/COMTask.csproj` |
| `TaskEditor` | C# | `TaskEditor/TaskEditor.csproj` |
| `VBTestTaskService` | VB.NET | `VBTestTaskService/VBTestTaskService.vbproj` |
| `TaskServiceExecutor` | C# | `TaskServiceExecutor/TaskServiceExecutor.csproj` |
| `SecurityEditor` | C# | `SecurityEditor/SecurityEditor.csproj` |
| `TestTaskService` | C# | `TestTaskService/TestTaskService.csproj` |

## How to open

Open `TaskService.sln` in Visual Studio.

## Attribution and provenance

- **Authors (package metadata):** David Hall
- **Assembly company:** CodePlex Community, Hewlett-Packard Company
- **Assembly copyright:** Copyright © 2012, Copyright © Hewlett-Packard Company 2008
- **Recorded URLs:** <http://taskscheduler.codeplex.com/>, <http://taskscheduler.codeplex.com/license>

## License

Original license terms apply where recorded in the tree or package metadata. This repository does not claim authorship. See `THIRD_PARTY_NOTICES.md`.
