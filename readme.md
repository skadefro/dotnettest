```
dotnet add package openiap

dotnet add package openiap -s ../openiap/dotnet/packages



rm -rf bin && dotnet nuget locals all --clear && dotnet add package openiap -s ../openiap/dotnet/packages && dotnet run 

rm -rf bin && dotnet nuget locals all --clear && dotnet add package openiap --version 0.0.15 && dotnet run 
```
```
dotnet nuget locals all --list
dotnet nuget locals all --clear
```