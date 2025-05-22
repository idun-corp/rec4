[Index](../../../../../../index.md) > [Point](../../../../../Point.md) > [Status](../../../../Status.md) > [On_Status](../../../On_Status.md) > [On_Off_Status](../../On_Off_Status.md) > [Start_Stop_Status](../Start_Stop_Status.md) > [Run_Status](#)
# Run_Status

**Display name:** Run Status<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Run_Status;1

---

## Child interfaces
* [Run_Request_Status](Run_Request_Status.md)

---

## Relationships

### Inherited Relationships
* **[Point](../../../../../Point.md):** isMemberOf, isPointOf, locatedIn

---

## Properties

### Inherited Properties
* **[Point](../../../../../Point.md):** aggregate, customProperties, customTags, hasQuantity, hasSubstance, identifiers, name
* **[Status](../../../../Status.md):** lastKnownValue

---

## Target Of
### General
* [Portfolio](../../../../../../Collection/Portfolio.md).includes
* [PointOfInterest](../../../../../../Information/PointOfInterest.md).objectOfInterest
* [Agent](../../../../../../Agent/Agent.md).owns
* [Space](../../../../../../Space/Space.md).isLocationOf
* [Lease](../../../../../../Event/Lease.md).leaseOf
* [Point](../../../../../Point.md).isPointOf
* [Document](../../../../../../Information/Document/Document.md).documentTopic
* [Document](../../../../../../Information/Document/Document.md).url
* [ServiceObject](../../../../../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Architecture](../../../../../../Space/Architecture/Architecture.md).isFedBy
* [System](../../../../../../Collection/System/System.md).includes
* [Equipment](../../../../../../Asset/Equipment/Equipment.md).feeds
* [Equipment](../../../../../../Asset/Equipment/Equipment.md).isFedBy
* [Meter](../../../../../../Asset/Equipment/Meter/Meter.md).meters
### Inherited
* [ActuationEvent](../../../../../../Event/Point-/ActuationEvent.md).targetPoint
* [Architecture](../../../../../../Space/Architecture/Architecture.md).hasPoint
* [Asset](../../../../../../Asset/Asset.md).hasPoint
* [ExceptionEvent](../../../../../../Event/Point-/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../../../../Event/Point-/ObservationEvent/ObservationEvent.md).sourcePoint
* [PointGroup](../../../../../../PointGroup.md).hasMember
* [ServiceObject](../../../../../../Information/ServiceObject/ServiceObject.md).producedBy
