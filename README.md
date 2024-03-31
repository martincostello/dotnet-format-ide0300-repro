# dotnet-format IDE0300 KeyNotFoundException Repro

Repro for [dotnet/sdk#39909](https://github.com/dotnet/sdk/issues/39909).

To reproduce the issue, clone this repository and run the following command:

```console
> dotnet format analyzers
Failed to apply code fix CSharpUseCollectionExpressionForArrayCodeFixProvider for IDE0300: The given key 'WorkspaceKinds' was not present in the dictionary.
```
