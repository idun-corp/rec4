[Index](../../../index.md) > [Event](../../Event.md) > [PointEvent](../PointEvent.md) > [ObservationEvent](ObservationEvent.md) > [MagneticFluxObservation](#)
# MagneticFluxObservation

**Display name:** Magnetic flux observation<br />
**DTMI:** dtmi:org:w3id:rec:MagneticFluxObservation;1

---

## Relationships

### Inherited Relationships
* **[ObservationEvent](ObservationEvent.md):** sourcePoint

---

## Properties

|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|value|**en**: value||double|True|
### Inherited Properties
* **[Event](../../Event.md):** customProperties, customTags, end, identifiers, name, start, timestamp

---

## Target Of
### General
* [Portfolio](../../../Collection/Portfolio.md).includes
* [PointOfInterest](../../../Information/PointOfInterest.md).objectOfInterest
* [Agent](../../../Agent/Agent.md).owns
* [Space](../../../Space/Space.md).isLocationOf
* [Lease](../../Lease.md).leaseOf
* [Point](../../../Point/Point.md).isPointOf
* [Document](../../../Information/Document/Document.md).documentTopic
* [Document](../../../Information/Document/Document.md).url
* [ServiceObject](../../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Architecture](../../../Space/Architecture/Architecture.md).isFedBy
* [System](../../../Collection/System/System.md).includes
* [Equipment](../../../Asset/Equipment/Equipment.md).feeds
* [Equipment](../../../Asset/Equipment/Equipment.md).isFedBy
* [Meter](../../../Asset/Equipment/Meter/Meter.md).meters
