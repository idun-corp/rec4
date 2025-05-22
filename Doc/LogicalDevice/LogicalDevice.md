[Index](../index.md) > [LogicalDevice](#)
# LogicalDevice

Logical Device.


**Display name:** LogicalDevice<br />
**DTMI:** dtmi:org:w3id:rec:LogicalDevice;1

---

## Child interfaces
* [LogicalServer](LogicalServer.md)

---

## Relationships

|Name|Display name|Description|Multiplicity|Target|Properties|Writable|
|-|-|-|-|-|-|-|
|hasPoint|**en**: has point||0-Infinity|[GatewayConnectionParameter](../Point/Parameter/GatewayConnection-/GatewayConnectionParameter.md)||True|
|locatedIn|**en**: located in||0-Infinity|[Space](../Space/Space.md)||True|
|servedBy|**en**: served by||0-1|[LogicalDevice](#)||True|
|serves|**en**: serves||0-Infinity|[LogicalDevice](#)||True|

---

## Properties

|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|customTags|**en**: Custom Tags||map (string->boolean)|True|
|identifiers|**en**: Identifiers||map (string->string)|True|
|name|**en**: name||string|True|

---

## Target Of
### General
* [Portfolio](../Collection/Portfolio.md).includes
* [PointOfInterest](../Information/PointOfInterest.md).objectOfInterest
* [Agent](../Agent/Agent.md).owns
* [Space](../Space/Space.md).isLocationOf
* [Lease](../Event/Lease.md).leaseOf
* [Point](../Point/Point.md).isPointOf
* [Document](../Information/Document/Document.md).documentTopic
* [Document](../Information/Document/Document.md).url
* [ServiceObject](../Information/ServiceObject/ServiceObject.md).relatedTo
* [Architecture](../Space/Architecture/Architecture.md).isFedBy
* [System](../Collection/System/System.md).includes
* [Equipment](../Asset/Equipment/Equipment.md).feeds
* [Equipment](../Asset/Equipment/Equipment.md).isFedBy
* [Meter](../Asset/Equipment/Meter/Meter.md).meters
### Direct
* [LogicalDevice](#).servedBy
* [LogicalDevice](#).serves
