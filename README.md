# ModbusCore API Documentation

This repository hosts the auto-generated API documentation for the ModbusCore library,
part of the Line Controller Embedded Platform developed at Vrije Universiteit Amsterdam.

## View the docs

👉 **[View API docs →](https://vu-elebate.github.io/modbuscore-docs/)**

## About

ModbusCore is a C/C++ library implementing the Modbus communication protocol.

## How docs are generated

Documentation is automatically generated from source code using [Doxygen](https://www.doxygen.nl/)
and deployed via the GitLab CI/CD pipeline on every push to `develop` or `main`.

To generate docs locally:
```bash
cd docs
doxygen Doxyfile
open html/index.html
```

## Source repository

The source code is maintained at:
[git.vu.nl/ele-b/line-controller-embedded-platform/modbuscore](https://git.vu.nl/ele-b/line-controller-embedded-platform/modbuscore)

## License

© Vrije Universiteit Amsterdam — Electronics Engineering Group
