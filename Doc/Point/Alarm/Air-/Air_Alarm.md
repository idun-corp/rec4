[Index](../../../index.md) > [Point](../../Point.md) > [Alarm](../Alarm.md) > [Air_Alarm](#)
# Air_Alarm

**Display name:** Air Alarm<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Air_Alarm;1

---

## Child interfaces
* [Air_Flow_Alarm](Air_Flow_Alarm/Air_Flow_Alarm.md)
* [Air_Temperature_Alarm](../Temperature-/Air-/Air_Temperature_Alarm.md)
* [Discharge_Air_Smoke_Detection_Alarm](../Smoke-/Smoke_Detection_Alarm/Discharge_Air-.md)
* [Supply_Air_Smoke_Detection_Alarm](../Smoke-/Smoke_Detection_Alarm/Supply_Air-.md)

---

## Components

### Inherited Components
* **[Alarm](../Alarm.md):** lastKnownValue

---

## Relationships

### Inherited Relationships
* **[Point](../../Point.md):** isMemberOf, isPointOf, locatedIn

---

## Properties

### Inherited Properties
* **[Point](../../Point.md):** aggregate, customProperties, customTags, hasQuantity, hasSubstance, identifiers, name

---

## Target Of
### General
* [Portfolio](../../../Collection/Portfolio.md).includes
* [PointOfInterest](../../../Information/PointOfInterest.md).objectOfInterest
* [Agent](../../../Agent/Agent.md).owns
* [Space](../../../Space/Space.md).isLocationOf
* [Lease](../../../Event/Lease.md).leaseOf
* [Point](../../Point.md).isPointOf
* [Document](../../../Information/Document/Document.md).documentTopic
* [Document](../../../Information/Document/Document.md).url
* [ServiceObject](../../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Architecture](../../../Space/Architecture/Architecture.md).isFedBy
* [System](../../../Collection/System/System.md).includes
* [Equipment](../../../Asset/Equipment/Equipment.md).feeds
* [Equipment](../../../Asset/Equipment/Equipment.md).isFedBy
* [Meter](../../../Asset/Equipment/Meter/Meter.md).meters
### Inherited
* [ActuationEvent](../../../Event/Point-/ActuationEvent.md).targetPoint
* [Architecture](../../../Space/Architecture/Architecture.md).hasPoint
* [Asset](../../../Asset/Asset.md).hasPoint
* [ExceptionEvent](../../../Event/Point-/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../Event/Point-/ObservationEvent/ObservationEvent.md).sourcePoint
* [PointGroup](../../../PointGroup.md).hasMember
* [ServiceObject](../../../Information/ServiceObject/ServiceObject.md).producedBy
