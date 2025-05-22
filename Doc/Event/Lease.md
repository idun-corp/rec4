[Index](../index.md) > [Event](Event.md) > [Lease](#)
# Lease

**Display name:** Lease<br />
**DTMI:** dtmi:org:w3id:rec:Lease;1

---

## Relationships

|Name|Display name|Description|Multiplicity|Target|Properties|Writable|
|-|-|-|-|-|-|-|
|leasee|**en**: leasee|**en**: The agent leasing some leasable object, i.e., the user of the asset.|0-Infinity|[Agent](../Agent/Agent.md)||True|
|leaseOf|**en**: lease of|**en**: The object (e.g., property, equipment, etc) that this a lease of.|0-Infinity|||True|
|leasor|**en**: leasor|**en**: The agent leasing out some leasable object, i.e., the owner of the asset.|0-Infinity|[Agent](../Agent/Agent.md)||True|
|regulatedBy|**en**: regulated by|**en**: Indicates the contract regulating the terms of the lease in question. |0-Infinity|[LeaseContract](../Information/Document/LeaseContract.md)||True|

---

## Properties

### Inherited Properties
* **[Event](Event.md):** customProperties, customTags, end, identifiers, name, start, timestamp

---

## Target Of
### General
* [Portfolio](../Collection/Portfolio.md).includes
* [PointOfInterest](../Information/PointOfInterest.md).objectOfInterest
* [Agent](../Agent/Agent.md).owns
* [Space](../Space/Space.md).isLocationOf
* [Lease](#).leaseOf
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
* [LeaseContract](../Information/Document/LeaseContract.md).regulates
