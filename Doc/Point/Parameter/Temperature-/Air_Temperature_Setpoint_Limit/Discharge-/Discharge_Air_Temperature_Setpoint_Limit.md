[Index](../../../../../index.md) > [Point](../../../../Point.md) > [Parameter](../../../Parameter.md) > [Temperature_Parameter](../../Temperature_Parameter.md) > [Air_Temperature_Setpoint_Limit](../Air_Temperature_Setpoint_Limit.md) > [Discharge_Air_Temperature_Setpoint_Limit](#)
# Discharge_Air_Temperature_Setpoint_Limit

A parameter that places a lower or upper bound on the range of permitted values of a Discharge_Air_Temperature_Setpoint.


**Display name:** Discharge Air Temperature Setpoint Limit<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Discharge_Air_Temperature_Setpoint_Limit;1

---

## Child interfaces
* [Max_Discharge_Air_Temperature_Setpoint_Limit](../../../Limit/Max-/Max_Temperature_Setpoint_Limit/Max_Discharge_Air_Temperature_Setpoint_Limit.md)
* [Min_Discharge_Air_Temperature_Setpoint_Limit](../../../Limit/Min-/Min_Temperature_Setpoint_Limit/Min_Discharge_Air_Temperature_Setpoint_Limit.md)

---

## Relationships

### Inherited Relationships
* **[Point](../../../../Point.md):** isMemberOf, isPointOf, locatedIn

---

## Properties

### Inherited Properties
* **[Parameter](../../../Parameter.md):** lastKnownValue
* **[Point](../../../../Point.md):** aggregate, customProperties, customTags, hasQuantity, hasSubstance, identifiers, name

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
