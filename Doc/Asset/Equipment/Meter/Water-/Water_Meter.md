[Index](../../../../index.md) > [Asset](../../../Asset.md) > [Equipment](../../Equipment.md) > [Meter](../Meter.md) > [Water_Meter](#)
# Water_Meter

A meter that measures the usage or consumption of water


**Display name:** Water Meter<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Water_Meter;1

---

## Child interfaces
* [Building_Water_Meter](Building-.md)
* [Chilled_Water_Meter](Chilled-/Chilled_Water_Meter.md)
* [Hot_Water_Meter](Hot-/Hot_Water_Meter.md)

---

## Relationships

### Inherited Relationships
* **[Equipment](../../Equipment.md):** feeds, isFedBy
* **[Meter](../Meter.md):** hasSubMeter, isSubMeterOf, meters
* **[Asset](../../../Asset.md):** commissionedBy, documentation, geometry, hasPart, hasPoint, installedBy, isPartOf, locatedIn, manufacturedBy, mountedOn, servicedBy

---

## Properties

### Inherited Properties
* **[Equipment](../../Equipment.md):** operationalStageCount
* **[Meter](../Meter.md):** isVirtualMeter
* **[Asset](../../../Asset.md):** assetTag, commissioningDate, customProperties, customTags, identifiers, initialCost, installationDate, IPAddress, MACAddress, maintenanceInterval, modelNumber, name, serialNumber, turnoverDate, weight

---

## Target Of
### General
* [Portfolio](../../../../Collection/Portfolio.md).includes
* [PointOfInterest](../../../../Information/PointOfInterest.md).objectOfInterest
* [Agent](../../../../Agent/Agent.md).owns
* [Space](../../../../Space/Space.md).isLocationOf
* [Lease](../../../../Event/Lease.md).leaseOf
* [Point](../../../../Point/Point.md).isPointOf
* [Document](../../../../Information/Document/Document.md).documentTopic
* [Document](../../../../Information/Document/Document.md).url
* [ServiceObject](../../../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Architecture](../../../../Space/Architecture/Architecture.md).isFedBy
* [System](../../../../Collection/System/System.md).includes
* [Equipment](../../Equipment.md).feeds
* [Equipment](../../Equipment.md).isFedBy
* [Meter](../Meter.md).meters
### Inherited
* [Loop](../../../../Collection/Loop/Loop.md).includes
* [Meter](../Meter.md).hasSubMeter
* [Meter](../Meter.md).isSubMeterOf
* [Asset](../../../Asset.md).hasPart
* [Asset](../../../Asset.md).isPartOf
* [EquipmentCollection](../../../../Collection/Equipment-.md).includes
* [PointGroup](../../../../PointGroup.md).isPointGroupOf
