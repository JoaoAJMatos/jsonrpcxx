# JSON RPC-2.0 C++ 17

## Introduction

This is a C++ 17 implementation of the [JSON RPC-2.0](https://www.jsonrpc.org/specification) protocol. It is an adaptation of Peter Spiess-Knafl's work on [JSON RPC-2.0 CXX](https://www.github.com/jsonrpcx/json-rpc-cxx) but rewritten as a single header file and with a few changes to the API.

## Features

- Single header
- JSON-RPC 2.0 compliant client/server
- Transport agnostic interfaces
- Compile time type mapping (using [nlohmann's]() arbitrary type conversion)
- Runtime type checking
- Cross platform (tested on Windows, Linux and OSX)

## Dependencies

This library uses nlohmann's json for modern C++ to handle JSON.

- [Nlohmann's JSON for modern C++](https://github.com/nlohmann/json)
- [Nlohmann's JSON for modern C++ (Header Only)](https://github.com/nlohmann/json/tree/develop/single_include/nlohmann)

Don't forget to update the include path to the json.hpp file in the header file.

## Usage

Checkout the [examples]() folder for a complete example.

### License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details