[Index](../../../index.md) > [Asset](../../Asset.md) > [ArchitecturalAsset](../ArchitecturalAsset.md) > [BarrierAsset](#)
# BarrierAsset

**Display name:** Barrier asset<br />
**DTMI:** dtmi:org:w3id:rec:BarrierAsset;1

---

## Child interfaces
* [AccessPanel](AccessPanel.md)
* [Door](Door.md)
* [Partition](Partition.md)
* [Window](Window.md)

---

## Relationships

### Inherited Relationships
* **[Asset](../../Asset.md):** commissionedBy, documentation, geometry, hasPart, hasPoint, installedBy, isPartOf, locatedIn, manufacturedBy, mountedOn, servicedBy

---

## Properties

### Inherited Properties
* **[Asset](../../Asset.md):** assetTag, commissioningDate, customProperties, customTags, identifiers, initialCost, installationDate, IPAddress, MACAddress, maintenanceInterval, modelNumber, name, serialNumber, turnoverDate, weight

---

## Target Of
### General
* [Portfolio](../../../Collection/Portfolio.md).includes
* [PointOfInterest](../../../Information/PointOfInterest.md).objectOfInterest
* [Agent](../../../Agent/Agent.md).owns
* [Space](../../../Space/Space.md).isLocationOf
* [Lease](../../../Event/Lease.md).leaseOf
* [Point](../../../Point/Point.md).isPointOf
* [Document](../../../Information/Document/Document.md).documentTopic
* [Document](../../../Information/Document/Document.md).url
* [ServiceObject](../../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Architecture](../../../Space/Architecture/Architecture.md).isFedBy
* [System](../../../Collection/System/System.md).includes
* [Equipment](../../Equipment/Equipment.md).feeds
* [Equipment](../../Equipment/Equipment.md).isFedBy
* [Meter](../../Equipment/Meter/Meter.md).meters
### Inherited
* [Asset](../../Asset.md).hasPart
* [Asset](../../Asset.md).isPartOf
* [PointGroup](../../../PointGroup.md).isPointGroupOf
