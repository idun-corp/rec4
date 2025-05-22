[Index](../../index.md) > [Asset](../Asset.md) > [Equipment](Equipment.md) > [Water_Distribution](#)
# Water_Distribution

Utilize a water distribution source to represent how water is distributed across multiple destinations (pipes)


**Display name:** Water Distribution<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Water_Distribution;1

---

## Relationships

### Inherited Relationships
* **[Equipment](Equipment.md):** feeds, isFedBy
* **[Asset](../Asset.md):** commissionedBy, documentation, geometry, hasPart, hasPoint, installedBy, isPartOf, locatedIn, manufacturedBy, mountedOn, servicedBy

---

## Properties

|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|tags|**en**: Tags|**en**: Brick tags associated with this interface.|map (string->boolean)|False|
### Inherited Properties
* **[Equipment](Equipment.md):** operationalStageCount
* **[Asset](../Asset.md):** assetTag, commissioningDate, customProperties, customTags, identifiers, initialCost, installationDate, IPAddress, MACAddress, maintenanceInterval, modelNumber, name, serialNumber, turnoverDate, weight

---

## Target Of
### General
* [Portfolio](../../Collection/Portfolio.md).includes
* [PointOfInterest](../../Information/PointOfInterest.md).objectOfInterest
* [Agent](../../Agent/Agent.md).owns
* [Space](../../Space/Space.md).isLocationOf
* [Lease](../../Event/Lease.md).leaseOf
* [Point](../../Point/Point.md).isPointOf
* [Document](../../Information/Document/Document.md).documentTopic
* [Document](../../Information/Document/Document.md).url
* [ServiceObject](../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Architecture](../../Space/Architecture/Architecture.md).isFedBy
* [System](../../Collection/System/System.md).includes
* [Equipment](Equipment.md).feeds
* [Equipment](Equipment.md).isFedBy
* [Meter](Meter/Meter.md).meters
### Inherited
* [Loop](../../Collection/Loop/Loop.md).includes
* [Asset](../Asset.md).hasPart
* [Asset](../Asset.md).isPartOf
* [EquipmentCollection](../../Collection/Equipment-.md).includes
* [PointGroup](../../PointGroup.md).isPointGroupOf
