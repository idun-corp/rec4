[Index](../../../index.md) > [Asset](../../Asset.md) > [Equipment](../Equipment.md) > [PV_Panel](#)
# PV_Panel

An integrated assembly of interconnected photovoltaic cells designed to deliver a selected level of working voltage and current at its output terminals packaged for protection against environment degradation and suited for incorporation in photovoltaic power systems.


**Display name:** PV Panel<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:PV_Panel;1

---

## Child interfaces
* [PVT_Panel](../Solar_Thermal_Collector/PVT_Panel.md)

---

## Relationships

### Inherited Relationships
* **[Equipment](../Equipment.md):** feeds, isFedBy
* **[Asset](../../Asset.md):** commissionedBy, documentation, geometry, hasPart, hasPoint, installedBy, isPartOf, locatedIn, manufacturedBy, mountedOn, servicedBy

---

## Properties

|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|measuredModuleConversionEfficiency|**en**: Measured module conversion efficiency||Microsoft.Azure.DigitalTwins.Parser.Models.DTObjectInfo|True|
|ratedModuleConversionEfficiency|**en**: Rated module conversion efficiency||Microsoft.Azure.DigitalTwins.Parser.Models.DTObjectInfo|True|
### Inherited Properties
* **[Equipment](../Equipment.md):** operationalStageCount
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
* [Equipment](../Equipment.md).feeds
* [Equipment](../Equipment.md).isFedBy
* [Meter](../Meter/Meter.md).meters
### Direct
* [PV_Array](../../../Collection/PV_Array.md).includes
### Inherited
* [Loop](../../../Collection/Loop/Loop.md).includes
* [Asset](../../Asset.md).hasPart
* [Asset](../../Asset.md).isPartOf
* [EquipmentCollection](../../../Collection/Equipment-.md).includes
* [PointGroup](../../../PointGroup.md).isPointGroupOf
