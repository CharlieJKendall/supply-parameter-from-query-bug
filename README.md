# supply-parameter-from-query-bug

https://github.com/dotnet/aspnetcore/issues/44781

- Give it a `dotnet run --project BlazorApp` from the root of the repository
- Navigate to http://localhost:5153 in browser
- Use anchor links to navigate between pages and observe multiple calls to `OnParametersSetAsync`