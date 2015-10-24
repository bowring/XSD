# XSD

This is a working repository for developing an xml schema for SHRIMP_PRAWN.

To validate an xml document against this schema, be sure the header is (for now):

```xml
<?xml version="1.0"?>
<!-- SHRIMP SW PRAWN Data File -->
<prawn_file xmlns="https://raw.githubusercontent.com"
            xmlns:xs="http://www.w3.org/2001/XMLSchema"
            xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
            xsi:schemaLocation="https://raw.githubusercontent.com
                                https://raw.githubusercontent.com/bowring/XSD/master/SHRIMP/SHRIMP_PRAWN.xsd">
```
