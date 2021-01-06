### Cheatsheets
- Markdown
  - [x] [https://www.markdownguide.org/cheat-sheet](https://www.markdownguide.org/cheat-sheet) ⭐
  - [x] GitHub Docs - Basic writing and formatting syntax ⭐
  - [x] github markdown emoji

### Commands / Shortcuts
- create a html skeleton in VS Code
  - enter ! or html:5 and tab
  
### Dotnet
- Useful libraries ⭐
  - ref: IAmTimCorey - 10 C# Libraries To Save You Time And Energy
  - [ ] Zip - SharpZipLib 
  - [ ] Mail - FluentEmail, MailKit, Papercut SMTP (local smtp server)
  - [ ] Excel import/export: EPPlus
  - [ ] Hangfire - job scheduling, execution, retry, dashboard
  - [ ] MassTransit - service bus abstraction for RabbitMQ, Azure Service Bus
  - [ ] Polly - handle transient fault, policy for retry, circuit breaker
  - [ ] Logging - Serilog (a substitute for log4net), Seq (structureed logging, log analysis)
  
- New Features in C# 9.0 ⭐
  - ref: IAmTimCorey
  - [ ] Top level Statements
  - [x] property init, can't change after calling constructor, e.g. string Name { get; init } = "Tim";
  - [x] Visual Studio>Tools >Options>Text Editor>C#>Advanced: display 'Inline Parameter name hint'
  - [x] No class name object initialisation, e.g. MyClass myclass = new ("firstname", 3);
  - [x] Task<MyResult> MyMethodAsync() { ... return Task.FromResult(results); }
  - [x] switch expression: - similar to inline ?; - use _ for default; - replace multiple if-else
  - [x] introduce and, or, not inside switch statement
  - [x] if (result is not null) vs if (result != null)
  - [ ] With expression

### Python
- Django web framework
- PyCharm IDE
- tips
  - [x] create a virtual environment, e.g. python -m venv c:\myenv
- Pandas
  - [x] data analysis library
  
### Tools
- Notepad++ (launch a new instance, e.g. notepad++.exe -multiInst -nosession)
- Pandoc ⭐
  - convert file formats, e.g. md to html, online html to offlie html, html to pdf
  - [x] pandoc -f markdown -t html test.txt -o test.html # md to html
  - [x] pandoc test.md -o test.pdf # md to pdf, need to install MiKTeX  
  - [x] pandoc -f html -t html https://www.fsf.org # online html to offline html
- Send anonymous email [https://www.guerrillamail.com](https://www.guerrillamail.com)
- Secure email (proton mail)
- Visual Studio Code ⭐
  - install Live Server
  - shortcuts
    - [x] Ctrl+` - go to the Terminal
    - [x] Ctrl+, - user settings
    - [x] Ctrl+X - delete a line
    - [x] Ctrl+K Ctrl+S - keyboard shortcuts
    - [x] Ctrl+Shift+` - create a new Terminal
    - [x] Ctrl+Shift+P - go to the Command Palette
    - [x] Ctrl+Shift+F - search all files in a folder, replace occurances
    - [x] Shift+Alt+Cursor - column block select
    - [x] Tab - Emmet expand abbreviation
  
