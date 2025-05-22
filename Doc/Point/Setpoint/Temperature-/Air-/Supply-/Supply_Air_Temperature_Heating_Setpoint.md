[Index](../../../../../index.md) > [Point](../../../../Point.md) > [Setpoint](../../../Setpoint.md) > [Temperature_Setpoint](../../Temperature_Setpoint.md) > [Air_Temperature_Setpoint](../Air_Temperature_Setpoint.md) > [Supply_Air_Temperature_Setpoint](Supply_Air_Temperature_Setpoint.md) > [Supply_Air_Temperature_Heating_Setpoint](#)
# Supply_Air_Temperature_Heating_Setpoint

**Display name:** Supply Air Temperature Heating Setpoint<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Supply_Air_Temperature_Heating_Setpoint;1

---

## Relationships

### Inherited Relationships
* **[Point](../../../../Point.md):** isMemberOf, isPointOf, locatedIn

---

## Properties

|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|tags|**en**: Tags|**en**: Brick tags associated with this interface.|map (string->boolean)|False|
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
