1. Add hello.proto and write content into hello.proto
2. Open poject root folder and cmd
3. Enter: packages\Grpc.Tools.2.45.0\tools\windows_x86\protoc.exe -I Greeter --csharp_out Greeter Greeter\hello.proto --grpc_out Greeter --plugin=protoc-gen-grpc=packages\Grpc.Tools.2.45.0\tools\windows_x86\grpc_csharp_plugin.exe
Ref:https://tw511.com/a/01/15702.html