# dotnet-format IDE0300 KeyNotFoundException Repro

Repro for `KeyNotFoundException` for IDE0300 with `dotnet format` in .NET 9 preview 2.

To reproduce the issue, clone this repository and run the following command:

```console
> dotnet format analyzers
Failed to apply code fix CSharpUseCollectionExpressionForArrayCodeFixProvider for IDE0300: The given key 'WorkspaceKinds' was not present in the dictionary.
```
