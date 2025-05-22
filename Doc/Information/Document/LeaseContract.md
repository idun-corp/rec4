[Index](../../index.md) > [Information](../Information.md) > [Document](Document.md) > [LeaseContract](#)
# LeaseContract

Formal document that identifies the Tenant and the leased asset or property; states lease term and fee (rent), and detailed terms and conditions of the lease agreement.


**Display name:** Lease contract<br />
**DTMI:** dtmi:org:w3id:rec:LeaseContract;1

---

## Relationships

|Name|Display name|Description|Multiplicity|Target|Properties|Writable|
|-|-|-|-|-|-|-|
|regulates|**en**: regulates|**en**: Indicates the lease(s) that this contract regulates the conditions of.|0-Infinity|[Lease](../../Event/Lease.md)||True|
### Inherited Relationships
* **[Document](Document.md):** documentTopic, url

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
* [Document](Document.md).documentTopic
* [Document](Document.md).url
* [ServiceObject](../ServiceObject/ServiceObject.md).relatedTo
* [Architecture](../../Space/Architecture/Architecture.md).isFedBy
* [System](../../Collection/System/System.md).includes
* [Equipment](../../Asset/Equipment/Equipment.md).feeds
* [Equipment](../../Asset/Equipment/Equipment.md).isFedBy
* [Meter](../../Asset/Equipment/Meter/Meter.md).meters
### Direct
* [Lease](../../Event/Lease.md).regulatedBy
### Inherited
* [Architecture](../../Space/Architecture/Architecture.md).documentation
* [Asset](../../Asset/Asset.md).documentation
* [BuildingElement](../../BuildingElement/BuildingElement.md).documentation
* [Collection](../../Collection/Collection.md).documentation
