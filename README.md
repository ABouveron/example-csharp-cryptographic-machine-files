# Example C# Cryptographic Machine Files

This is an example of how to verify and decrypt cryptographic machine files in C#
and .NET, using Ed25519 and AES-256-GCM.

## Running the example

First, install dependencies with [`dotnet`](https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet):

```
dotnet restore
```

Then run the program:

```
dotnet run
```

You should see log output indicating the current machine file is valid as well
as its decrypted contents:

```
Machine file is valid! Decrypting...
Machine file was successfully decrypted!
Decrypted: ...
```

## Questions?

Reach out at [support@keygen.sh](mailto:support@keygen.sh) if you have any
questions or concerns!
