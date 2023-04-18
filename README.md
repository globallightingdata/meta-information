# GLDF meta-information

This repository contains the XML Schema for the [meta-information.xml](https://gldf.io/docs/container/meta-information/) file of the [**G**lobal **L**ighting **D**ata **F**ormat](https://gldf.io)

## Example

```xml
<?xml version="1.0" encoding="UTF-8"?>
<MetaInformation xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
                 xsi:noNamespaceSchemaLocation="meta-information.xsd">
  <Property name="companyA-SetttingA">Value of setting A</Property>
  <Property name="companyB-SetttingA">Value of setting A</Property>
  <Property name="companyB-SetttingB">Value of setting B</Property>
</MetaInformation>
```
