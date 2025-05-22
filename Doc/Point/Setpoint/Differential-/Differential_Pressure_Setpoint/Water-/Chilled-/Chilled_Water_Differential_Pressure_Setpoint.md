[Index](../../../../../../index.md) > [Point](../../../../../Point.md) > [Setpoint](../../../../Setpoint.md) > [Differential_Setpoint](../../../Differential_Setpoint.md) > [Differential_Pressure_Setpoint](../../Differential_Pressure_Setpoint.md) > [Water_Differential_Pressure_Setpoint](../Water_Differential_Pressure_Setpoint.md) > [Chilled_Water_Differential_Pressure_Setpoint](#)
# Chilled_Water_Differential_Pressure_Setpoint

Sets the target water differential pressure between an upstream and downstream point in a water pipe or conduit used to carry chilled water


**Display name:** Chilled Water Differential Pressure Setpoint<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Chilled_Water_Differential_Pressure_Setpoint;1

---

## Child interfaces
* [Chilled_Water_Differential_Pressure_Load_Shed_Setpoint](Chilled_Water_Differential_Pressure_Load_Shed_Setpoint.md)

---

## Relationships

### Inherited Relationships
* **[Point](../../../../../Point.md):** isMemberOf, isPointOf, locatedIn

---

## Properties

### Inherited Properties
* **[Point](../../../../../Point.md):** aggregate, customProperties, customTags, hasQuantity, hasSubstance, identifiers, name
* **[Setpoint](../../../../Setpoint.md):** lastKnownValue

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
