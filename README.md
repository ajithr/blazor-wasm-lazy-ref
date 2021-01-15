# blazor-wasm-lazy-ref
Blazor WASM lazy loading assemblies not working with @ref attribute.

## To reproduce the issue

* Check out the above repo and open `~/LazyLoadingRef/LazyLoadingRef.csproj` file in the `VS 2019`.
* Run the application it will throw exceptions in the browser console.
* Open `~/LazyLoadingRef/Pages/Counter.razor` file and remove `@ref` attribute and `LazyLoadComponent` reference in the `@code` section.
* Run the sample again and it will work properly with the lazy loading feature.
