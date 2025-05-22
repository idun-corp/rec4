[Index](../../../index.md) > [Point](../../Point.md) > [Setpoint](../Setpoint.md) > [Deadband_Setpoint](#)
# Deadband_Setpoint

Sets the size of a deadband


**Display name:** Deadband Setpoint<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Deadband_Setpoint;1

---

## Child interfaces
* [Air_Flow_Deadband_Setpoint](../Flow-/Air-/Air_Flow_Deadband_Setpoint/Air_Flow_Deadband_Setpoint.md)
* [Humidity_Deadband_Setpoint](Humidity-.md)
* [Static_Pressure_Deadband_Setpoint](../Pressure-/Static-/Static_Pressure_Deadband_Setpoint/Static_Pressure_Deadband_Setpoint.md)
* [Temperature_Deadband_Setpoint](../Temperature-/Temperature_Deadband_Setpoint/Temperature_Deadband_Setpoint.md)

---

## Relationships

### Inherited Relationships
* **[Point](../../Point.md):** isMemberOf, isPointOf, locatedIn

---

## Properties

### Inherited Properties
* **[Point](../../Point.md):** aggregate, customProperties, customTags, hasQuantity, hasSubstance, identifiers, name
* **[Setpoint](../Setpoint.md):** lastKnownValue

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
