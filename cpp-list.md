## C/C++

### Base Library
- [POCO](http://pocoproject.org/) - Modern, powerful open source C++ class libraries for building network- and internet-based applications that run on desktop, server, mobile and embedded systems.
- [Atria](http://abletonag.github.io/atria/) - Atria is a toolkit for modern C++ development. It provides core components that extend the standard library's capabilities. It provides (mostly) header-only libraries of general interest, in the spirit of the STL, Boost, Adobe Source Libraries or Facebook's Folly and Fatal.
- [BDE](https://github.com/bloomberg/bde) - Basic Development Environment - a set of foundational C++ libraries used at Bloomberg. http://bloomberglabs.com/bde

### Desktop Framework
- [CopperSpice](http://www.copperspice.com/) - CopperSpice is a C++ library derived from the existing Qt 4.8 framework. Our goal was to change the core design of the libraries, leveraging template functionality and C++11 capabilities.
- [Chromium Embedded Framework](https://bitbucket.org/chromiumembedded/cef) - The Chromium Embedded Framework (CEF) is a simple framework for embedding Chromium-based browsers in other applications.
- [XULRunner](https://developer.mozilla.org/en-US/docs/Mozilla/Projects/XULRunner) - XULRunner is a Mozilla runtime package that can be used to bootstrap XUL+XPCOM applications that are as rich as Firefox and Thunderbird. It provides mechanisms for installing, upgrading, and uninstalling these applications. XULRunner also provides libxul, a solution which allows the embedding of Mozilla technologies in other projects and products.

### Web Framework
- [Wt](http://www.webtoolkit.eu/wt) - Wt (pronounced as witty) is a C++ library for developing web applications. The API is widget-centric and uses well-tested patterns of desktop GUI development tailored to the web. 
- [Crow](https://github.com/ipkn/crow) - Crow is very fast and easy to use C++ micro web framework (inspired by Python Flask)
- [pistache](https://github.com/oktal/pistache/) - Pistache is a modern and elegant HTTP and REST framework for C++. It is entirely written in pure-C++11 and provides a clear and pleasant API.
- [beast](https://github.com/boostorg/beast) - Beast is a C++ header-only library serving as a foundation for writing interoperable networking libraries by providing low-level HTTP/1, WebSocket, and networking protocol vocabulary types and algorithms using the consistent asynchronous model of Boost.Asio.

### Application Framework
- [Seastar](https://github.com/scylladb/seastar) - SeaStar is an event-driven framework allowing you to write non-blocking, asynchronous code in a relatively straightforward manner (once understood). It is based on futures.

### Actor Framework
- [CAF_C++ Actor Framework](http://actor-framework.org/) - An Open Source Implementation  of the Actor Model in C++.
- [SObjectizer](http://sourceforge.net/projects/sobjectizer/) - SObjectizer is a small tool for simplification of development of concurrent and event-driven applications in C++. It was used for projects of various sizes: from very small utilities to large distributed and highly loaded applications.

### Event-Driven
- [libev](http://software.schmorp.de/pkg/libev.html) - A full-featured and high-performance (see benchmark) event loop that is loosely modelled after libevent, but without its limitations and bugs. It is used in GNU Virtual Private Ethernet, rxvt-unicode, auditd, the Deliantra MORPG Server and Client, and many other programs.
- [libevent](http://libevent.org/) - The libevent API provides a mechanism to execute a callback function when a specific event occurs on a file descriptor or after a timeout has been reached. Furthermore, libevent also support callbacks due to signals or regular timeouts.
- [libuv](http://libuv.org/) - libuv is a multi-platform support library with a focus on asynchronous I/O.

### Callback Framework
- [libsigc++](http://libsigc.sourceforge.net/) - libsigc++ implements a typesafe callback system for standard C++. It allows you to define signals and to connect those signals to any callback function, either global or a member function, regardless of whether it is static or virtual.

### Cross Language Binding
- [Djinni](https://github.com/dropbox/djinni) - Djinni is a tool for generating cross-language type declarations and interface bindings. It's designed to connect C++ with either Java or Objective-C. Python support is available in an experimental version on the python branch.

### Concurrent Library
- [CDS](http://libcds.sourceforge.net/) - CDS is a C++ template library of lock-free and fine-grained algorithms. It contains a collection of concurrent data structure implementations.

### Function
- [Fit](https://github.com/pfultz2/Fit) - Fit is a header-only C++11 library that provides utilities for functions and function objects.

### Generator
- [cpp_range](https://github.com/whoshuu/cpp_range) - Python-like range iterators for C++

### Format
- [cppformat](https://github.com/cppformat/cppformat) - C++ Format is an open-source formatting library for C++. It can be used as a safe alternative to printf or as a fast alternative to IOStreams.

### Media
- [SDL](http://www.libsdl.org/) - Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D.

### Math
- [Libmvec](https://sourceware.org/glibc/wiki/libmvec) - Libmvec is vector math library added in Glibc 2.22.
- [LibGeoDecomp](http://libgeodecomp.org/index.html) - LibGeoDecomp is an auto-parallelizing library to speed up your stencil code based computer simulations. It runs on virtually all current architectures, be it multi-cores, GPUs, or large scale MPI clusters.

### Embedded Application
- [macchina](http://macchina.io/) - macchina.io is an open source software toolkit for quickly building embedded applications for the Internet of Things that run on Linux-based devices like the Raspberry Pi, Beaglebone, RED Brick or Galileo/Edison.

### Package Manager
- [Biicode](https://www.biicode.com/) - C and C++ Dependency Manager with CMake on steroids
- [Conan](https://github.com/conan-io/conan) - A binary dependency manager and hosting service for developers
- [Hunter](https://github.com/ruslo/hunter) - Cross-platform package manager for C++ (based on CMake ExternalProject). Linux, Mac, Windows, iOS, Android, Raspberry Pi.
- [Pants](http://www.pantsbuild.org/) - Pants is a build system supports Java, Scala, Python, C/C++, Go, Javascript/Node, Thrift, Protobuf and Android code. Adding support for other languages, frameworks and code generators is straightforward.

### Linter
- [flint](https://github.com/facebook/flint) - An open-source lint program for C++ developed by, and used at Facebook.

### Memory
- [jemalloc](http://www.canonware.com/jemalloc/) - jemalloc is a general purpose malloc(3) implementation that emphasizes fragmentation avoidance and scalable concurrency support.

### Protocol
- [Thrift](https://thrift.apache.org/) - The Apache Thrift software framework, for scalable cross-language services development, combines a software stack with a code generation engine to build services that work efficiently and seamlessly between C++, Java, Python, PHP, Ruby, Erlang, Perl, Haskell, C#, Cocoa, JavaScript, Node.js, Smalltalk, OCaml and Delphi and other languages.
- [FlatBuffers](https://google.github.io/flatbuffers/) - FlatBuffers is an efficient cross platform serialization library for C++, with support for Java, C# and Go. It was created at Google specifically for game development and other performance-critical applications.
- [MessagePack](http://msgpack.org/) - MessagePack is an efficient binary serialization format. It lets you exchange data among multiple languages like JSON. But it's faster and smaller. Small integers are encoded into a single byte, and typical short strings require only one extra byte in addition to the strings themselves.
- [Avro](https://avro.apache.org/) - Apache Avro™ is a data serialization system.
- [Aeron](https://github.com/real-logic/Aeron) - Efficient reliable UDP unicast, UDP multicast, and IPC message transport.
- [tchannel](https://github.com/uber/tchannel) - Network multiplexing and framing protocol for RPC.
- [cereal](https://github.com/USCiLab/cereal) - cereal is a header-only C++11 serialization library. cereal takes arbitrary data types and reversibly turns them into different representations, such as compact binary encodings, XML, or JSON. 

### PRC
- [rpclib](http://rpclib.net/) - Welcome! rpclib is a msgpack-rpc library written using modern C++. The goal of this library is to provide a simple, no-nonsense RPC solution.

### JSON Parser
- [GoldFish](https://github.com/OneNoteDev/GoldFish) - A fast JSON and CBOR streaming library, without using memory

### Immutable
- [immer](https://github.com/arximboldi/immer) - Postmodern immutable and persistent data structures for C++ https://sinusoid.es/immer

### Network
- [libtins](http://libtins.github.io/) - libtins is a high-level, multiplatform C++ network packet sniffing and crafting library.
- [cpp-netlib](http://cpp-netlib.org/) - A collection of open-source libraries for high level network programming.
- [ENet](http://enet.bespin.org/) - ENet's purpose is to provide a relatively thin, simple and robust network communication layer on top of UDP (User Datagram Protocol).The primary feature it provides is optional reliable, in-order delivery of packets.

### Crypto
- [botan](https://github.com/randombit/botan) - Botan (Japanese for peony) is a cryptography library written in C++11 and released under the permissive Simplified BSD license.

### Signal/Slot
- [nano-signal-slot](https://github.com/NoAvailableAlias/nano-signal-slot) - Pure C++11 Signals and Slots

### Test
- [CDSChecker](http://plrg.eecs.uci.edu/software_page/42-2/) - CDSChecker is a model checker for C11/C++11 which exhaustively explores the behaviors of code under the C/C++ memory model. It uses partial order reduction as well as a few other novel techniques to eliminate time spent on redundant execution behaviors and to significantly shrink the state space.
- [CPP Testing Example](https://github.com/spencewenski/cpp_testing_example)- This is an example of how to set up Google testing frameworks for a project.
- [CUTE](http://www.cute-test.com/) - CUTE is an easy to use C++ unit testing framework that leverages modern C++ libraries and features. CUTE is orthogonal, easily extendable and much simpler than other C++ unit testing approaches like CPPUnit. For example, CUTE does not require that you write a derived class for each C++ class you want to unit test.
- [Catch](https://github.com/philsquared/Catch) - A modern, C++-native, header-only, test framework for unit-tests, TDD and BDD - using C++98, C++03, C++11, C++14 and later http://catch-lib.net

### IDE
- [CLion](https://www.jetbrains.com/clion/) - This powerful IDE helps you develop in C and C++ on Linux, OS X and Windows, enhancing your productivity with a smart editor, code quality assurance, automated refactorings, and deep integration with CMake build system.
- [Cevelop](https://www.cevelop.com/) - The C++ IDE for professional developers

### Robot
- [Robot](https://github.com/Robot/robot) - Introducing Robot for C++, a library aimed at facilitating the development of system automation software for the purposes of test automation, self-running demos, and other applications.

### logging
- [spdlog](https://github.com/gabime/spdlog) - Very fast, header only, C++ logging library.

### HTTP
- [http-parser](https://github.com/nodejs/http-parser) - This is a parser for HTTP messages written in C. It parses both requests and responses. The parser is designed to be used in performance HTTP applications.

### Windows
- [cppwinrt](https://github.com/microsoft/cppwinrt) - C++/WinRT is a standard C++ language projection for the Windows Runtime.
