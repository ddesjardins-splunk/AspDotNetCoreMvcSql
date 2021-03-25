# AspDotNetCoreMvcSql

1. Download Visual Studio 2019 community
2. Edit Startup.cs as follows:
3.  Change the bottom line to point to YOUR Collector using Otel GRPC endpoint. 
    otlpOptions.Endpoint = new Uri("http://40.78.131.7:4317");
4. Press Play.
