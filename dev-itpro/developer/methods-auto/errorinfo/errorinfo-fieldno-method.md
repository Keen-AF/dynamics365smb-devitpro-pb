---
title: "ErrorInfo.FieldNo([Integer]) Method"
description: "Specifies the field ID that the error relates to."
ms.author: solsen
ms.date: 08/26/2024
ms.topic: reference
author: SusanneWindfeldPedersen
ms.reviewer: solsen
---
[//]: # (START>DO_NOT_EDIT)
[//]: # (IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT.)
[//]: # (Any modifications should be made in the .xml files in the ModernDev repo.)
# ErrorInfo.FieldNo([Integer]) Method
> **Version**: _Available or changed with runtime version 8.0._

Specifies the field ID that the error relates to.


## Syntax
```AL
[FieldNo := ]  ErrorInfo.FieldNo([FieldNo: Integer])
```
> [!NOTE]
> This method can be invoked using property access syntax.
## Parameters
*ErrorInfo*  
&emsp;Type: [ErrorInfo](errorinfo-data-type.md)  
An instance of the [ErrorInfo](errorinfo-data-type.md) data type.  

*[Optional] FieldNo*  
&emsp;Type: [Integer](../integer/integer-data-type.md)  
The field ID of the ErrorInfo  


## Return Value
*[Optional] FieldNo*  
&emsp;Type: [Integer](../integer/integer-data-type.md)  
The current field ID of the ErrorInfo.


[//]: # (IMPORTANT: END>DO_NOT_EDIT)
## Related information

[Collecting Errors](../../devenv-error-collection.md)  
[ErrorInfo Data Type](errorinfo-data-type.md)  
[Get Started with AL](../../devenv-get-started.md)  
[Developing Extensions](../../devenv-dev-overview.md)