[Index](../../../../../index.md) > [Point](../../../../Point.md) > [Setpoint](../../../Setpoint.md) > [Temperature_Setpoint](../../Temperature_Setpoint.md) > [Air_Temperature_Setpoint](../Air_Temperature_Setpoint.md) > [Occupied_Air_Temperature_Setpoint](#)
# Occupied_Air_Temperature_Setpoint

**Display name:** Occupied Air Temperature Setpoint<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Occupied_Air_Temperature_Setpoint;1

---

## Child interfaces
* [Occupied_Air_Temperature_Cooling_Setpoint](Occupied_Air_Temperature_Cooling_Setpoint.md)
* [Occupied_Air_Temperature_Heating_Setpoint](Occupied_Air_Temperature_Heating_Setpoint.md)
* [Occupied_Discharge_Air_Temperature_Setpoint](Occupied_Discharge_Air_Temperature_Setpoint.md)
* [Occupied_Return_Air_Temperature_Setpoint](../Return-/Occupied-.md)
* [Occupied_Room_Air_Temperature_Setpoint](../Room-/Occupied-.md)
* [Occupied_Supply_Air_Temperature_Setpoint](../Supply-/Occupied-.md)
* [Occupied_Zone_Air_Temperature_Setpoint](../Zone-/Occupied-.md)

---

## Relationships

### Inherited Relationships
* **[Point](../../../../Point.md):** isMemberOf, isPointOf, locatedIn

---

## Properties

### Inherited Properties
* **[Point](../../../../Point.md):** aggregate, customProperties, customTags, hasQuantity, hasSubstance, identifiers, name
* **[Setpoint](../../../Setpoint.md):** lastKnownValue

---

## Target Of
### General
* [Portfolio](../../../../../Collection/Portfolio.md).includes
* [PointOfInterest](../../../../../Information/PointOfInterest.md).objectOfInterest
* [Agent](../../../../../Agent/Agent.md).owns
* [Space](../../../../../Space/Space.md).isLocationOf
* [Lease](../../../../../Event/Lease.md).leaseOf
* [Point](../../../../Point.md).isPointOf
* [Document](../../../../../Information/Document/Document.md).documentTopic
* [Document](../../../../../Information/Document/Document.md).url
* [ServiceObject](../../../../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Architecture](../../../../../Space/Architecture/Architecture.md).isFedBy
* [System](../../../../../Collection/System/System.md).includes
* [Equipment](../../../../../Asset/Equipment/Equipment.md).feeds
* [Equipment](../../../../../Asset/Equipment/Equipment.md).isFedBy
* [Meter](../../../../../Asset/Equipment/Meter/Meter.md).meters
### Inherited
* [ActuationEvent](../../../../../Event/Point-/ActuationEvent.md).targetPoint
* [Architecture](../../../../../Space/Architecture/Architecture.md).hasPoint
* [Asset](../../../../../Asset/Asset.md).hasPoint
* [ExceptionEvent](../../../../../Event/Point-/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../../../Event/Point-/ObservationEvent/ObservationEvent.md).sourcePoint
* [PointGroup](../../../../../PointGroup.md).hasMember
* [ServiceObject](../../../../../Information/ServiceObject/ServiceObject.md).producedBy
