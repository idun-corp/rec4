[Index](../../../../index.md) > [Asset](../../../Asset.md) > [Equipment](../../Equipment.md) > [HVAC_Equipment](../HVAC_Equipment.md) > [Terminal_Unit](#)
# Terminal_Unit

A device that regulates the volumetric flow rate and/or the temperature of the controlled medium.


**Display name:** Terminal Unit<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Terminal_Unit;1

---

## Child interfaces
* [Air_Diffuser](Air_Diffuser/Air_Diffuser.md)
* [CAV](CAV.md)
* [Chilled_Beam](Chilled_Beam/Chilled_Beam.md)
* [Constant_Air_Volume_Box](Constant_Air_Volume_Box.md)
* [Fan_Coil_Unit](Fan_Coil_Unit.md)
* [FCU](FCU.md)
* [Induction_Unit](Induction_Unit.md)
* [Radiant_Panel](Radiant_Panel/Radiant_Panel.md)
* [Radiator](Radiator/Radiator.md)
* [Variable_Air_Volume_Box](Variable_Air_Volume_Box/Variable_Air_Volume_Box.md)
* [VAV](VAV.md)

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
