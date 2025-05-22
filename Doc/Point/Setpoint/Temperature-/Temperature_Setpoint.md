[Index](../../../index.md) > [Point](../../Point.md) > [Setpoint](../Setpoint.md) > [Temperature_Setpoint](#)
# Temperature_Setpoint

Sets temperature


**Display name:** Temperature Setpoint<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Temperature_Setpoint;1

---

## Child interfaces
* [Air_Temperature_Setpoint](Air-/Air_Temperature_Setpoint.md)
* [Cooling_Temperature_Setpoint](Cooling-/Cooling_Temperature_Setpoint.md)
* [Heating_Temperature_Setpoint](Heating-/Heating_Temperature_Setpoint.md)
* [Radiant_Panel_Temperature_Setpoint](Radiant_Panel-/Radiant_Panel_Temperature_Setpoint.md)
* [Schedule_Temperature_Setpoint](Schedule-.md)
* [Temperature_Deadband_Setpoint](Temperature_Deadband_Setpoint/Temperature_Deadband_Setpoint.md)
* [Water_Temperature_Setpoint](Water-/Water_Temperature_Setpoint.md)

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
