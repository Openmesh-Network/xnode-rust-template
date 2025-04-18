## Xnode Rust Template

Template to make your Rust app Xnode/Nix compatible.

## Modification Steps

1. Replace all instances of "xnode-rust-template" with the name of your project. This should be unique, as no apps with the same name can be run on a single Xnode.
2. Build your Rust app
4. Once your app is ready for deployment and runs using `nix run`, push to GitHub and copy your GitHub url (e.g. https://github.com/Openmesh-Network/xnode-rust-template).
5. Go the the App Store in [Xnode Studio](https://www.openmesh.network/xnode/app-store) and go to the advanced tab.
6. Paste your GitHub url and enter the name of the project you choose during step 1.
7. Hit deploy and wait for your app to be ready.
8. Copy the deploy link and replace the one click deployment url in the next section. (to allow others to easily deploy your application)

## One click deployment

[<img src="https://www.openmesh.network/xnode/deploy-on-xnode.svg" width=200 />](https://www.openmesh.network/xnode/deploy?advanced=eyJkYXRhIjp7Im5hbWUiOiJ4bm9kZS1ydXN0LXRlbXBsYXRlIiwiZGVzYyI6IkN1c3RvbSBBcHAiLCJuaXhOYW1lIjoieG5vZGUtcnVzdC10ZW1wbGF0ZSIsIm9wdGlvbnMiOlt7Im5hbWUiOiJlbmFibGUiLCJkZXNjIjoiRW5hYmxlIHRoZSBuZXh0anMgYXBwIiwibml4TmFtZSI6ImVuYWJsZSIsInR5cGUiOiJib29sZWFuIiwidmFsdWUiOiJ0cnVlIn0seyJuYW1lIjoiaG9zdG5hbWUiLCJkZXNjIjoiVGhlIGhvc3RuYW1lIHVuZGVyIHdoaWNoIHRoZSBhcHAgc2hvdWxkIGJlIGFjY2Vzc2libGUuIiwibml4TmFtZSI6Imhvc3RuYW1lIiwidHlwZSI6InN0cmluZyIsInZhbHVlIjoiMC4wLjAuMCJ9LHsibmFtZSI6InBvcnQiLCJkZXNjIjoiVGhlIHBvcnQgdW5kZXIgd2hpY2ggdGhlIGFwcCBzaG91bGQgYmUgYWNjZXNzaWJsZS4iLCJuaXhOYW1lIjoicG9ydCIsInR5cGUiOiIxNiBiaXQgdW5zaWduZWQgaW50ZWdlcjsgYmV0d2VlbiAwIGFuZCA2NTUzNSAoYm90aCBpbmNsdXNpdmUpIiwidmFsdWUiOiIzMDAwIn0seyJuYW1lIjoib3BlbkZpcmV3YWxsIiwiZGVzYyI6IldoZXRoZXIgdG8gb3BlbiBwb3J0cyBpbiB0aGUgZmlyZXdhbGwgZm9yIHRoaXMgYXBwbGljYXRpb24uIiwibml4TmFtZSI6Im9wZW5GaXJld2FsbCIsInR5cGUiOiJib29sZWFuIiwidmFsdWUiOiJ0cnVlIn1dLCJ0YWdzIjpbXSwiZmxha2VzIjpbeyJuYW1lIjoieG5vZGUtcnVzdC10ZW1wbGF0ZS1mbGFrZSIsInVybCI6ImdpdGh1YjpPcGVubWVzaC1OZXR3b3JrL3hub2RlLXJ1c3QtdGVtcGxhdGUifV0sImlkIjoieG5vZGUtcnVzdC10ZW1wbGF0ZSJ9LCJ0eXBlIjoidGVtcGxhdGVzIiwic2VydmljZXMiOlt7Im5hbWUiOiJ4bm9kZS1ydXN0LXRlbXBsYXRlIiwiZGVzYyI6IkN1c3RvbSBBcHAiLCJuaXhOYW1lIjoieG5vZGUtcnVzdC10ZW1wbGF0ZSIsIm9wdGlvbnMiOlt7Im5hbWUiOiJlbmFibGUiLCJkZXNjIjoiRW5hYmxlIHRoZSBuZXh0anMgYXBwIiwibml4TmFtZSI6ImVuYWJsZSIsInR5cGUiOiJib29sZWFuIiwidmFsdWUiOiJ0cnVlIn0seyJuYW1lIjoiaG9zdG5hbWUiLCJkZXNjIjoiVGhlIGhvc3RuYW1lIHVuZGVyIHdoaWNoIHRoZSBhcHAgc2hvdWxkIGJlIGFjY2Vzc2libGUuIiwibml4TmFtZSI6Imhvc3RuYW1lIiwidHlwZSI6InN0cmluZyIsInZhbHVlIjoiMC4wLjAuMCJ9LHsibmFtZSI6InBvcnQiLCJkZXNjIjoiVGhlIHBvcnQgdW5kZXIgd2hpY2ggdGhlIGFwcCBzaG91bGQgYmUgYWNjZXNzaWJsZS4iLCJuaXhOYW1lIjoicG9ydCIsInR5cGUiOiIxNiBiaXQgdW5zaWduZWQgaW50ZWdlcjsgYmV0d2VlbiAwIGFuZCA2NTUzNSAoYm90aCBpbmNsdXNpdmUpIiwidmFsdWUiOiIzMDAwIn0seyJuYW1lIjoib3BlbkZpcmV3YWxsIiwiZGVzYyI6IldoZXRoZXIgdG8gb3BlbiBwb3J0cyBpbiB0aGUgZmlyZXdhbGwgZm9yIHRoaXMgYXBwbGljYXRpb24uIiwibml4TmFtZSI6Im9wZW5GaXJld2FsbCIsInR5cGUiOiJib29sZWFuIiwidmFsdWUiOiJ0cnVlIn1dLCJ0YWdzIjpbXSwiZmxha2VzIjpbeyJuYW1lIjoieG5vZGUtcnVzdC10ZW1wbGF0ZS1mbGFrZSIsInVybCI6ImdpdGh1YjpPcGVubWVzaC1OZXR3b3JrL3hub2RlLXJ1c3QtdGVtcGxhdGUifV19XX0=)

## Commands (in root folder)

```
nix run
```

## Commands (in rust-app)

```
cargo build
cargo run
```
