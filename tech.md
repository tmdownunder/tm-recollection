### Cheatsheets
- Markdown
  - [x] [https://www.markdownguide.org/cheat-sheet](https://www.markdownguide.org/cheat-sheet) ⭐
  - [x] GitHub Docs - Basic writing and formatting syntax ⭐

### Commands / Shortcuts
- creat a html skeleton in VS Code
  - enter ! or html:5
  
### Dotnet
- Useful libraries (ref: IAmTimCorey - 10 C# Libraries To Save You Time And Energy): ⭐
  - [ ] Zip - SharpZipLib 
  - [ ] Mail - FluentEmail, MailKit, Papercut SMTP (local smtp server)
  - [ ] Excel import/export: EPPlus
  - [ ] Hangfire - job scheduling, execution, retry, dashboard
  - [ ] MassTransit - service bus abstraction for RabbitMQ, Azure Service Bus
  - [ ] Polly - handle transient fault, policy for retry, circuit breaker
  - [ ] Logging - Serilog (a substitute for log4net), Seq (structureed logging, log analysis)
  
- 5 New Features in C# 9.0 (ref: IAmTimCorey) ⭐
  - [ ] Top level Statements
  - [x] property init, can't change after calling constructor, e.g. string Name { get; init } = "Tim";
  - [x] Visual Studio>Tools >Options>Text Editor>C#>Advanced: display 'Inline Parameter name hint'
  - [x] No class name object initialisation, e.g. MyClass myclass = new ("firstname", 3);
  - [x] Task<MyResult> MyMethodAsync() { ... return Task.FromResult(results); }
  - [x] switch expression: - similar to inline ?; - use _ for default; - replace multiple if-else
  - [x] introduce and, or, not inside switch statement
  - [x] if (result is not null) vs if (result != null)
  - [ ] With expression

### Tools
- Pandoc (a tool to convert file formats, e.g. md to html, online html to offlie html, html to pdf) ⭐
  - [x] pandoc -f markdown -t html test.txt -o test.html # md to html
  - [x] pandoc -f html -t html https://www.fsf.org # online html to offlie html
- Send anonymous email [https://www.guerrillamail.com](https://www.guerrillamail.com)
- Secure email (proton mail)
- Notepad++ (launch a new instance, e.g. notepad++.exe -multiInst -nosession)
