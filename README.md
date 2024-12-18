# `Go` gRPC Remote Procedure Calls

This project includes four **server - client** examples using **`gRPC`**. It implements the **same** functionality as the original **`Python`** code by rewriting it in **`Go`**.

*※ Related Course: [SWCON492] Full-Stack Service Networking* <br>
*※ **Error handling** added to the original source code*

<br>

### Original Source Code Runtime Environment
: <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=Python&logoColor=white" width=10%>&nbsp;
<img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" width=10%>&nbsp;
<img src="https://img.shields.io/badge/-grpc-%23305F65?style=for-the-badge" width=6%>&nbsp;
<img src="https://img.shields.io/badge/Poetry-%233B82F6.svg?style=for-the-badge&logo=poetry&logoColor=0B3D8D" width=9.5%>

### Project Runtime Environment
: <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=Go&logoColor=white" width=6.5%>&nbsp;
<img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" width=10%>&nbsp;
<img src="https://img.shields.io/badge/-grpc-%23305F65?style=for-the-badge" width=6%>

<br>

## Project Structure

```
simple_grpc_go/
├── lec-07-prg-01-hello_gRPC
│   ├── client.go
│   ├── server.go
│   └── hello_gRPC
│   │   ├── hello_grpc.go
│   │   ├── hello_grpc_grpc.pb.go
│   │   ├── hello_grpc.pb.go
│   │   └── hello_grpc.proto
├── lec-07-prg-02-bidirectional-streaming
│   ├── client.go
│   ├── server.go
│   └── bidirectional
│   │   ├── bidirectional_grpc.pb.go
│   │   ├── bidirectional.pb.go
│   │   └── bidirectional.proto
├── lec-07-prg-03-clientstreaming
│   ├── client.go
│   ├── server.go
│   └── clientstreaming
│   │   ├── clientstreaming_grpc.pb.go
│   │   ├── clientstreaming.pb.go
│   │   └── clientstreaming.proto
├── lec-07-prg-04-serverstreaming
│   ├── client.go
│   ├── server.go
│   └── serverstreaming
│       ├── serverstreaming_grpc.pb.go
│       ├── serverstreaming.pb.go
│       └── serverstreaming.proto
├── go.mod
├── go.sum
└── README.md
```
