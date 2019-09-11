---
layout: post
title:  "FileRenamer (C# WPF)"
date:   2019-05-24 17:18:06 +0200
categories: C#
---
Das Programm ändert eine große Anzahl von Dateien in einem Ordner. Zum Suchen und Ersetzen kann Regex verwendet werden. [Link zum Repository](https://github.com/k3yro/Tools/tree/master/FileRenamer "FileRenamer Repo")

![Alt text](https://github.com/k3yro/Tools/tree/master/FileRenamer/Screenshot.PNG?raw=true "Screenshot")

[Download (v1.0)](https://github.com/k3yro/Tools/releases/download/v1.0/Setup.exe "Download")
## Requirements
- [.Net Framework 4.7.2](https://dotnet.microsoft.com/download/dotnet-framework/net472 "Microsofts's Homepage") (or higher)
- A folder full of files
## Regex Syntax
| Syntax   |  Description  |
|----------|:-------------:|
| ^        |  Begin of filename |
| $        |  End of filename   |
| \s       | Whitespace |
|[A-z]     | Find chars A-z |

[Download Regex Beschreibung im (.pdf) Format](https://download.microsoft.com/download/D/2/4/D240EBF6-A9BA-4E4F-A63F-AEB6DA0B921C/Regular%20expressions%20quick%20reference.pdf "Microsofts's Homepage")