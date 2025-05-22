[Index](../../../../index.md) > [Asset](../../../Asset.md) > [Equipment](../../Equipment.md) > [HVAC_Equipment](../HVAC_Equipment.md) > [Filter](#)
# Filter

Device to remove gases from a mixture of gases or to remove solid material from a fluid


**Display name:** Filter<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Filter;1

---

## Child interfaces
* [Final_Filter](Final-.md)
* [Intake_Air_Filter](Intake_Air-.md)
* [Mixed_Air_Filter](Mixed_Air-.md)
* [Pre_Filter](Pre-.md)
* [Return_Air_Filter](Return_Air-.md)

---

## Relationships

### Inherited Relationships
* **[Equipment](../../Equipment.md):** feeds, isFedBy
* **[Asset](../../../Asset.md):** commissionedBy, documentation, geometry, hasPart, hasPoint, installedBy, isPartOf, locatedIn, manufacturedBy, mountedOn, servicedBy

---

## Properties

### Inherited Properties
* **[Equipment](../../Equipment.md):** operationalStageCount
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
* [Meter](../../Meter/Meter.md).meters
### Inherited
* [Loop](../../../../Collection/Loop/Loop.md).includes
* [Asset](../../../Asset.md).hasPart
* [Asset](../../../Asset.md).isPartOf
* [EquipmentCollection](../../../../Collection/Equipment-.md).includes
* [PointGroup](../../../../PointGroup.md).isPointGroupOf
