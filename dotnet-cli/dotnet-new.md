---
description: >-
  Agar siz windows operatsion tizimni ishlatsangiz cmd yoki powershellga dotnet build kommandasini yozasiz. Linux yoki MacOS tizimdan foydalansangiz terminalni ishlatasiz.
---

# dotnet new

Terminalga **dotnet new** kommandasini yozish orqali siz dotnet loyiha shablonini yaratishingiz mumkin. Ammo **new** kalit so'zidan so'ng loyiha shabloni nomi yozilishni talab qiladi.
Loyiha shablon nomlari ro'yxati quydagicha:

 - ASP.NET Core Empty                            web                  [C#],F#     Web/Empty
 - ASP.NET Core gRPC Service                     grpc                 [C#]        Web/gRPC
 - ASP.NET Core Web API                          webapi               [C#],F#     Web/WebAPI
 - ASP.NET Core Web App                          webapp,razor         [C#]        Web/MVC/Razor Pages
 - ASP.NET Core Web App (Model-View-Controller)  mvc                  [C#],F#     Web/MVC
 - ASP.NET Core with Angular                     angular              [C#]        Web/MVC/SPA
 - ASP.NET Core with React.js                    react                [C#]        Web/MVC/SPA
 - Blazor Server App                             blazorserver         [C#]        Web/Blazor
 - Blazor WebAssembly App                        blazorwasm           [C#]        Web/Blazor/ - WebAssembly/PWA
 - Class Library                                 classlib             [C#],F#,VB  Common/Library
 - Console App                                   console              [C#],F#,VB  Common/Console
 - dotnet gitignore file                         gitignore                        Config
 - Dotnet local tool manifest file               tool-manifest                    Config
 - EditorConfig file                             editorconfig                     Config
 - global.json file                              globaljson                       Config
 - MSTest Test Project                           mstest               [C#],F#,VB  Test/MSTest
 - MVC ViewImports                               viewimports          [C#]        Web/ASP.NET
 - MVC ViewStart                                 viewstart            [C#]        Web/ASP.NET
 - NuGet Config                                  nugetconfig                      Config
 - NUnit 3 Test Item                             nunit-test           [C#],F#,VB  Test/NUnit
 - NUnit 3 Test Project                          nunit                [C#],F#,VB  Test/NUnit
 - Protocol Buffer File                          proto                            Web/gRPC
 - Razor Class Library                           razorclasslib        [C#]        Web/Razor/Library
 - Razor Component                               razorcomponent       [C#]        Web/ASP.NET
 - Razor Page                                    page                 [C#]        Web/ASP.NET
 - Solution File                                 sln                              Solution
 - Web Config                                    webconfig                        Config
 - Windows Forms App                             winforms             [C#],VB     Common/WinForms
 - Windows Forms Class Library                   winformslib          [C#],VB     Common/WinForms
 - Windows Forms Control Library                 winformscontrollib   [C#],VB     Common/WinForms
 - Worker Service                                worker               [C#],F#     Common/Worker/Web
 - WPF Application                               wpf                  [C#],VB     Common/WPF
 - WPF Class Library                             wpflib               [C#],VB     Common/WPF
 - WPF Custom Control Library                    wpfcustomcontrollib  [C#],VB     Common/WPF
 - WPF User Control Library                      wpfusercontrollib    [C#],VB     Common/WPF
 - xUnit Test Project                            xunit                [C#],F#,VB  Test/xUnit  

Misol uchun
```csharp
dotnet new console --name Simple
```
Komandasini yozish orqali **Simple** nomli konsole dastur uchun shablon yaratib olasiz..
