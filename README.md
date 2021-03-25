# AspDotNetCoreMvcSql

1. Download Visual Studio 2019
2. Edit Startup.cs as follows:
3.  Change the bottom line to point to YOUR Collector using Otel GRPC endpoint. 
    otlpOptions.Endpoint = new Uri("http://40.78.131.7:4317");
4. Build it.
5. You will likey need to add NuGet Packages to get it to build. ( you will be prompted if necessary )
6. Once built, Press play
7. CREATE a NEW MOVIE Entry triggers the AZure Function
8. ALL operations hit SQL server and should show up in map/traces.
