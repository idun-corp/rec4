[Index](../index.md) > [LogicalDevice](LogicalDevice.md) > [LogicalServer](#)
# LogicalServer

Logical Server.


**Display name:** LogicalServer<br />
**DTMI:** dtmi:org:w3id:rec:LogicalServer;1

---

## Relationships

### Inherited Relationships
* **[LogicalDevice](LogicalDevice.md):** hasPoint, locatedIn, servedBy, serves

---

## Properties

|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|IPAddress|**en**: IP address||string|True|
### Inherited Properties
* **[LogicalDevice](LogicalDevice.md):** customTags, identifiers, name

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
### Inherited
* [LogicalDevice](LogicalDevice.md).servedBy
* [LogicalDevice](LogicalDevice.md).serves
