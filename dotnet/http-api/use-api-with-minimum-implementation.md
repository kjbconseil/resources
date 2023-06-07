# How use externals API with minimum implementation of it ?

Have a look onto [Refit library](https://github.com/reactiveui/refit), which allow developers to only define interface and somme attributes.
The library will configure for us ``HttpRequestMessage``, ``HttpClient`` and other stuff.
Of course, we can customize headers, query, filters, etc..
It simplify the way to consume the API.

More example here : 
* https://code-maze.com/using-refit-to-consume-apis-in-csharp/
