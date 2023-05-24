# Introduction

URML is a general mathematics computing language, aiming to be an open source and portable. The language is designed to be simple to understand for non-programmers through an intuitive syntax. Additionally, URML is meant to be modular, providing interfaces for user interfaces.

These set of documents describe URML's open source language reference.

<br />

**Design goals:**

Open, modular, and portable:
- URML is open source, thus providing a free and accessible alternative for general purpose mathematical computing.
- Modular: No assumptions are made towards using a specific interface application, or other enhancements. URML is a language first, meant to run independently. However, URML provides interfaces to allow for any user interface for purposes such as plotting, any plugins, etc.
- Portable: URML can be run through an interpreter, in addition to providing a compiled execution option. URML's modular design also makes URML more portable, as different enhancements for different platforms can be programmed to work with URML, as long as it follows our provided interfaces.

Fast and efficient:
- Compiled execution option: In addition to being able to be executed through an interpreter, URML code can also be executed through a compiled source. This is helpful when certain resource-intensive and processing-heavy sub-computations have been perfected, and can thus be compiled for faster execution.
- GPU accelerated: Multiple operations available in the standard library for data types URML provides are GPU accelerated, such as several vector and matrix operations.
- Distributed computing execution: URML design encourages modular programming and in addition, provides many out of the box features to allow for URML code and programs to be executed using distributed computing, whether it be through computers linked in a local network or a cloud service.

Programmer friendly:
- Namespaces: URML provides easy namespacing features. These namespacing features are also used with the provided standard library,providing more visibility into the features URML offers.
- Global types: URML makes it easy to create global data, such as strings, errors, etc. to allow programmers to create a consistent program, thus allowing for an easier and better debugging experience.
- LaTeX integration: URML integrated LaTeX into places such as comment sections, thus making it easier for mathematicians to convey ideas about certain sub-programs.
