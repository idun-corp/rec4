[Index](../../../index.md) > [Point](../../Point.md) > [Setpoint](../Setpoint.md) > [Differential_Setpoint](#)
# Differential_Setpoint

A type of Setpoints that is related to the difference between two measurements


**Display name:** Differential Setpoint<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Differential_Setpoint;1

---

## Child interfaces
* [Differential_Pressure_Deadband_Setpoint](Differential_Pressure_Deadband_Setpoint/Differential_Pressure_Deadband_Setpoint.md)
* [Differential_Pressure_Setpoint](Differential_Pressure_Setpoint/Differential_Pressure_Setpoint.md)
* [Differential_Speed_Setpoint](Differential_Speed_Setpoint.md)
* [Differential_Temperature_Setpoint](Differential_Temperature_Setpoint/Differential_Temperature_Setpoint.md)
* [Medium_Temperature_Hot_Water_Differential_Pressure_Load_Shed_Setpoint](Medium_Temperature_Hot_Water_Differential_Pressure_Load_Shed_Setpoint.md)
* [Temperature_Differential_Reset_Setpoint](Temperature_Differential_Reset_Setpoint/Temperature_Differential_Reset_Setpoint.md)

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
