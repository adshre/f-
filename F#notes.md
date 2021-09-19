- Terminal commmand to check installation version => dotnet --version
- In visual studio - got to market place extension(last option in side navbar) and search, select and install ionide-fsharp
- .NET Interactive: https://github.com/dotnet/interactive (Remaining)
- F# interactive is REPL - reads code, executes it and prints outpul immediately  in the console. and does this in a loop
- Terminal : To start REPL => donet fsi
- End of expression  by ;; so we can have multiple expressions  and we can evaluate  them later at the end with ;;
  - ex : printfn "HellowWorld"\
         printfn "Hi" ;;
- To exit terminal  => #q;;
- File saved with .fsx extention and doesnot need ;;
- External Package usage in file => Use #r before package
- Nuget is package manager for .net
- Syntax for external package import is #r "nuget:pacakgeName,version"
- Beginner documentation  : https://aka.ms/learn-fsharp
- Time claculation in terminal : /usr/bin/time dotnet fsi A.fsx


