[Index](../index.md) > [Collection](Collection.md) > [Portfolio](#)
# Portfolio

A portfolio is a grouping of buildings, sites, apartments, campuses, etc. that share some business-relevant commonality, e.g., are managed by the same company, are rented out to the same tenant, share utilization or legal definition (industrial vs commercial), etc.


**Display name:** Portfolio<br />
**DTMI:** dtmi:org:w3id:rec:Portfolio;1

---

## Relationships

|Name|Display name|Description|Multiplicity|Target|Properties|Writable|
|-|-|-|-|-|-|-|
|includes|**en**: includes||0-Infinity|||True|
### Inherited Relationships
* **[Collection](Collection.md):** documentation

---

## Properties

### Inherited Properties
* **[Collection](Collection.md):** customProperties, customTags, identifiers, name

---

## Target Of
### General
* [Portfolio](#).includes
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
