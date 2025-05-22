[Index](../../../index.md) > [Point](../../Point.md) > [Parameter](../Parameter.md) > [GatewayConnectionParameter](#)
# GatewayConnectionParameter

**Display name:** Gateway Connection Parameter<br />
**DTMI:** dtmi:org:w3id:rec:GatewayConnectionParameter;1

---

## Child interfaces
* [IoTHubConnectionParameter](IoTHubConnectionParameter.md)

---

## Relationships

### Inherited Relationships
* **[Point](../../Point.md):** isMemberOf, isPointOf, locatedIn

---

## Properties

|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|gatewayType|**en**: gateway type||string|True|
### Inherited Properties
* **[Parameter](../Parameter.md):** lastKnownValue
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
### Direct
* [LogicalDevice](../../../LogicalDevice/LogicalDevice.md).hasPoint
### Inherited
* [ActuationEvent](../../../Event/Point-/ActuationEvent.md).targetPoint
* [Architecture](../../../Space/Architecture/Architecture.md).hasPoint
* [Asset](../../../Asset/Asset.md).hasPoint
* [ExceptionEvent](../../../Event/Point-/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../Event/Point-/ObservationEvent/ObservationEvent.md).sourcePoint
* [PointGroup](../../../PointGroup.md).hasMember
* [ServiceObject](../../../Information/ServiceObject/ServiceObject.md).producedBy
