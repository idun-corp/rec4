[Index](../../../../../index.md) > [Asset](../../../../Asset.md) > [Equipment](../../../Equipment.md) > [HVAC_Equipment](../../HVAC_Equipment.md) > [Terminal_Unit](../Terminal_Unit.md) > [Variable_Air_Volume_Box](Variable_Air_Volume_Box.md) > [Variable_Air_Volume_Box_With_Reheat](#)
# Variable_Air_Volume_Box_With_Reheat

A VAV box with a reheat coil mounted on the discharge end of the unit that can heat the air delivered to a zone


**Display name:** Variable Air Volume Box With Reheat<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Variable_Air_Volume_Box_With_Reheat;1

---

## Relationships

### Inherited Relationships
* **[Equipment](../../../Equipment.md):** feeds, isFedBy
* **[Asset](../../../../Asset.md):** commissionedBy, documentation, geometry, hasPart, hasPoint, installedBy, isPartOf, locatedIn, manufacturedBy, mountedOn, servicedBy

---

## Properties

|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|tags|**en**: Tags|**en**: Brick tags associated with this interface.|map (string->boolean)|False|
### Inherited Properties
* **[Equipment](../../../Equipment.md):** operationalStageCount
* **[Asset](../../../../Asset.md):** assetTag, commissioningDate, customProperties, customTags, identifiers, initialCost, installationDate, IPAddress, MACAddress, maintenanceInterval, modelNumber, name, serialNumber, turnoverDate, weight

---

## Target Of
### General
* [Portfolio](../../../../../Collection/Portfolio.md).includes
* [PointOfInterest](../../../../../Information/PointOfInterest.md).objectOfInterest
* [Agent](../../../../../Agent/Agent.md).owns
* [Space](../../../../../Space/Space.md).isLocationOf
* [Lease](../../../../../Event/Lease.md).leaseOf
* [Point](../../../../../Point/Point.md).isPointOf
* [Document](../../../../../Information/Document/Document.md).documentTopic
* [Document](../../../../../Information/Document/Document.md).url
* [ServiceObject](../../../../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Architecture](../../../../../Space/Architecture/Architecture.md).isFedBy
* [System](../../../../../Collection/System/System.md).includes
* [Equipment](../../../Equipment.md).feeds
* [Equipment](../../../Equipment.md).isFedBy
* [Meter](../../../Meter/Meter.md).meters
### Inherited
* [Loop](../../../../../Collection/Loop/Loop.md).includes
* [Asset](../../../../Asset.md).hasPart
* [Asset](../../../../Asset.md).isPartOf
* [EquipmentCollection](../../../../../Collection/Equipment-.md).includes
* [PointGroup](../../../../../PointGroup.md).isPointGroupOf
