[Index](../../../index.md) > [Collection](../../Collection.md) > [Loop](../Loop.md) > [Water_Loop](Water_Loop.md) > [Domestic_Water_Loop](#)
# Domestic_Water_Loop

**Display name:** Domestic Water Loop<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Domestic_Water_Loop;1

---

## Relationships

### Inherited Relationships
* **[Loop](../Loop.md):** includes
* **[Collection](../../Collection.md):** documentation

---

## Properties

|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|tags|**en**: Tags|**en**: Brick tags associated with this interface.|map (string->boolean)|False|
### Inherited Properties
* **[Collection](../../Collection.md):** customProperties, customTags, identifiers, name

---

## Target Of
### General
* [Portfolio](../../Portfolio.md).includes
* [PointOfInterest](../../../Information/PointOfInterest.md).objectOfInterest
* [Agent](../../../Agent/Agent.md).owns
* [Space](../../../Space/Space.md).isLocationOf
* [Lease](../../../Event/Lease.md).leaseOf
* [Point](../../../Point/Point.md).isPointOf
* [Document](../../../Information/Document/Document.md).documentTopic
* [Document](../../../Information/Document/Document.md).url
* [ServiceObject](../../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Architecture](../../../Space/Architecture/Architecture.md).isFedBy
* [System](../../System/System.md).includes
* [Equipment](../../../Asset/Equipment/Equipment.md).feeds
* [Equipment](../../../Asset/Equipment/Equipment.md).isFedBy
* [Meter](../../../Asset/Equipment/Meter/Meter.md).meters
