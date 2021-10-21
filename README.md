# PowerDocu
After you have built a Flow in Power Automate, you may consider documenting it as to allow others to get a better understanding of how it works, to ensure that any specific configuration in it is kept somewhere else as well, or for other reasons. However, manually documenting the technical implementation can be quite time consuming.

This is where **FlowDocumenter** can help!dotnet

Currently, this repository contains a solution to document Power Automate Flows, called **FlowDocumenter**. FlowDocumenter allows the automatic generation of technical documentation based on a provided exported Flow package.

![Example of generated Word documentation](Images/Weather-Flow-Documentation-1.png)
![Example of generated Word documentation](Images/Weather-Flow-Documentation-2.png)


## What is generated as part of the technical documentation?

The documentation includes

1. A generated Word document including sections on
    1. General information of the Flow
    2. The connectors that are used by the Flow
    3. The Trigger that starts the Flow
    4. The actions used in the Flow
    5. A high-level and a detailed diagram of the Flow
2. PNG and SVG renditions of the high-level and details diagrams


> **_NOTE:_** FlowDocumenter is currently in a very early development stage. It offers basic functionality, but has a lot of room for improvement. If you find any bugs or other issues, please log an **[Issue](https://github.com/modery/PowerDocu/issues)** in this GitHub project. For any improvement recommendations and suggestions, please open a **[Discussion](https://github.com/modery/PowerDocu/discussion)**. Most importantly, if you want to contribute to this project's code, please fork this repository and submit appropriate Pull Requests. **Any kind of contribution is more than welcome!**

## How to use

Please refer to [Installation & Usage](installation.md) for information on how to install FlowDocumenter and how to use it to generate documentation.

## How does the generated documentation look like?

Please have a look at the [examples](examples.md) provided.
