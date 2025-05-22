[Index](../index.md) > [Collection](Collection.md) > [FurnitureCollection](#)
# FurnitureCollection

**Display name:** Furniture collection<br />
**DTMI:** dtmi:org:w3id:rec:FurnitureCollection;1

---

## Relationships

|Name|Display name|Description|Multiplicity|Target|Properties|Writable|
|-|-|-|-|-|-|-|
|includes|**en**: includes||0-Infinity|[Furniture](../Asset/Furniture/Furniture.md)||True|
### Inherited Relationships
* **[Collection](Collection.md):** documentation

---

## Properties

### Inherited Properties
* **[Collection](Collection.md):** customProperties, customTags, identifiers, name

---

## Target Of
### General
* [Portfolio](Portfolio.md).includes
* [PointOfInterest](../Information/PointOfInterest.md).objectOfInterest
* [Agent](../Agent/Agent.md).owns
* [Space](../Space/Space.md).isLocationOf
* [Lease](../Event/Lease.md).leaseOf
* [Point](../Point/Point.md).isPointOf
* [Document](../Information/Document/Document.md).documentTopic
* [Document](../Information/Document/Document.md).url
* [ServiceObject](../Information/ServiceObject/ServiceObject.md).relatedTo
* [Architecture](../Space/Architecture/Architecture.md).isFedBy
* [System](System/System.md).includes
* [Equipment](../Asset/Equipment/Equipment.md).feeds
* [Equipment](../Asset/Equipment/Equipment.md).isFedBy
* [Meter](../Asset/Equipment/Meter/Meter.md).meters
