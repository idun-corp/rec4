[Index](../../index.md) > [Information](../Information.md) > [Document](#)
# Document

**Display name:** Document<br />
**DTMI:** dtmi:org:w3id:rec:Document;1

---

## Child interfaces
* [LeaseContract](LeaseContract.md)

---

## Relationships

|Name|Display name|Description|Multiplicity|Target|Properties|Writable|
|-|-|-|-|-|-|-|
|documentTopic|**en**: document topic||0-Infinity|||True|
|url|**en**: URL||0-Infinity|||True|

---

## Properties

### Inherited Properties
* **[Information](../Information.md):** customProperties, customTags, identifiers, name

---

## Target Of
### General
* [Portfolio](../../Collection/Portfolio.md).includes
* [PointOfInterest](../PointOfInterest.md).objectOfInterest
* [Agent](../../Agent/Agent.md).owns
* [Space](../../Space/Space.md).isLocationOf
* [Lease](../../Event/Lease.md).leaseOf
* [Point](../../Point/Point.md).isPointOf
* [Document](#).documentTopic
* [Document](#).url
* [ServiceObject](../ServiceObject/ServiceObject.md).relatedTo
* [Architecture](../../Space/Architecture/Architecture.md).isFedBy
* [System](../../Collection/System/System.md).includes
* [Equipment](../../Asset/Equipment/Equipment.md).feeds
* [Equipment](../../Asset/Equipment/Equipment.md).isFedBy
* [Meter](../../Asset/Equipment/Meter/Meter.md).meters
### Direct
* [Architecture](../../Space/Architecture/Architecture.md).documentation
* [Asset](../../Asset/Asset.md).documentation
* [BuildingElement](../../BuildingElement/BuildingElement.md).documentation
* [Collection](../../Collection/Collection.md).documentation
