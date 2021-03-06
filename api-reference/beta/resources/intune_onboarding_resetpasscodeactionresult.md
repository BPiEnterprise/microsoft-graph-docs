﻿# resetPasscodeActionResult resource type> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://www.microsoft.com/en-us/cloud-platform/microsoft-intune-pricing) by the customer.

Reset passcode action result

Inherits from [deviceActionResult](../resources/intune_onboarding_deviceactionresult.md)

### Properties
|Property|Type|Description|
|---|---|---|
|actionName|String|Action name Inherited from [deviceActionResult](../resources/intune_onboarding_deviceactionresult.md)|
|actionState|String|State of the action Inherited from [deviceActionResult](../resources/intune_onboarding_deviceactionresult.md) Possible values are: `none`, `pending`, `cancel`, `active`, `done`, `failed`, `notSupported`.|
|startDateTime|DateTimeOffset|Time the action was initiated Inherited from [deviceActionResult](../resources/intune_onboarding_deviceactionresult.md)|
|lastUpdatedDateTime|DateTimeOffset|Time the action state was last updated Inherited from [deviceActionResult](../resources/intune_onboarding_deviceactionresult.md)|
|passcode|String|Newly generated passcode for the device |

### Relationships
None
### JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.resetPasscodeActionResult"
}
-->
```json
{
  "@odata.type": "#microsoft.graph.resetPasscodeActionResult",
  "actionName": "String",
  "actionState": "String",
  "startDateTime": "String (timestamp)",
  "lastUpdatedDateTime": "String (timestamp)",
  "passcode": "String"
}
```



