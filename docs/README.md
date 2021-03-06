# Document Generator

_automatically generate Google Documents based on templates and modules_

![](example.png)

### Goals

1. Quickly create documents with increased accuracy
2. Decentralize authoring and avoid monolithic templates
3. Have more fun

### Use

![](install.png)

### Templates

_document generator uses Templates to define the sections of a document_

- templates must start with the name **<template:**

![](template-example.png)

- create named sections in your template with the **{sectionName}** syntax:

![](template-example-outline.png)

### Modules

_document generator uses Modules to define the content of a document's sections_

- modules must start with the name **<module:**

![](module-example.png)

- create named sections in your module with the **{sectionName}** syntax:

![](module-example-outline.png)

### Example

_Let's use Document Generator to create a proposal! The tool will allow us to select a template, select a module for each section of the template, and fill out necessary information as defined in each module..._

![](generate.gif)

### Caveats

- If you're using images in your modules, make sure they are **inline** images, otherwise they won't copy over!
- Make sure modules and templates you create are available on our [shared Google drive](https://drive.google.com/drive/folders/1VKnYUI9Q4j1BVCRurhqnVR2bV3OjMDbL) so everyone can use them!
