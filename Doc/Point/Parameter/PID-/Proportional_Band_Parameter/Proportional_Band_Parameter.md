[Index](../../../../index.md) > [Point](../../../Point.md) > [Parameter](../../Parameter.md) > [PID_Parameter](../PID_Parameter.md) > [Proportional_Band_Parameter](#)
# Proportional_Band_Parameter

**Display name:** Proportional Band Parameter<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Proportional_Band_Parameter;1

---

## Child interfaces
* [Differential_Pressure_Proportional_Band](Differential_Pressure_Proportional_Band/Differential_Pressure_Proportional_Band.md)
* [Discharge_Air_Temperature_Proportional_Band_Parameter](Discharge_Air_Temperature-/Discharge_Air_Temperature_Proportional_Band_Parameter.md)
* [Entering_Water_Temperature_Proportional_Band_Parameter](Entering_Water_Temperature-.md)
* [Exhaust_Air_Flow_Proportional_Band_Parameter](Exhaust_Air_Flow-/Exhaust_Air_Flow_Proportional_Band_Parameter.md)
* [Leaving_Water_Temperature_Proportional_Band_Parameter](Leaving_Water_Temperature-.md)
* [Static_Pressure_Proportional_Band_Parameter](Static_Pressure-/Static_Pressure_Proportional_Band_Parameter.md)
* [Supply_Air_Temperature_Proportional_Band_Parameter](Supply_Air_Temperature-/Supply_Air_Temperature_Proportional_Band_Parameter.md)

---

## Relationships

### Inherited Relationships
* **[Point](../../../Point.md):** isMemberOf, isPointOf, locatedIn

---

## Properties

### Inherited Properties
* **[Parameter](../../Parameter.md):** lastKnownValue
* **[Point](../../../Point.md):** aggregate, customProperties, customTags, hasQuantity, hasSubstance, identifiers, name

---

## Target Of
### General
* [Portfolio](../../../../Collection/Portfolio.md).includes
* [PointOfInterest](../../../../Information/PointOfInterest.md).objectOfInterest
* [Agent](../../../../Agent/Agent.md).owns
* [Space](../../../../Space/Space.md).isLocationOf
* [Lease](../../../../Event/Lease.md).leaseOf
* [Point](../../../Point.md).isPointOf
* [Document](../../../../Information/Document/Document.md).documentTopic
* [Document](../../../../Information/Document/Document.md).url
* [ServiceObject](../../../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Architecture](../../../../Space/Architecture/Architecture.md).isFedBy
* [System](../../../../Collection/System/System.md).includes
* [Equipment](../../../../Asset/Equipment/Equipment.md).feeds
* [Equipment](../../../../Asset/Equipment/Equipment.md).isFedBy
* [Meter](../../../../Asset/Equipment/Meter/Meter.md).meters
### Inherited
* [ActuationEvent](../../../../Event/Point-/ActuationEvent.md).targetPoint
* [Architecture](../../../../Space/Architecture/Architecture.md).hasPoint
* [Asset](../../../../Asset/Asset.md).hasPoint
* [ExceptionEvent](../../../../Event/Point-/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../../Event/Point-/ObservationEvent/ObservationEvent.md).sourcePoint
* [PointGroup](../../../../PointGroup.md).hasMember
* [ServiceObject](../../../../Information/ServiceObject/ServiceObject.md).producedBy
