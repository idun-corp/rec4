[Index](../../../../index.md) > [Asset](../../../Asset.md) > [Equipment](../../Equipment.md) > [ICTEquipment](../ICTEquipment.md) > [SensorEquipment](#)
# SensorEquipment

Sensor equipment.


**Display name:** Sensor Equipment<br />
**DTMI:** dtmi:org:w3id:rec:SensorEquipment;1

---

## Child interfaces
* [DaylightSensorEquipment](Daylight-.md)
* [IAQSensorEquipment](IAQ-.md)
* [LeakDetectorEquipment](LeakDetectorEquipment.md)
* [OccupancySensorEquipment](Occupancy-.md)
* [PeopleCountSensorEquipment](PeopleCount-.md)
* [ThermostatEquipment](ThermostatEquipment.md)
* [VibrationSensorEquipment](Vibration-.md)

---

## Relationships

### Inherited Relationships
* **[Equipment](../../Equipment.md):** feeds, isFedBy
* **[Asset](../../../Asset.md):** commissionedBy, documentation, geometry, hasPart, hasPoint, installedBy, isPartOf, locatedIn, manufacturedBy, mountedOn, servicedBy

---

## Properties

|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|batteryPercentage|**en**: Battery Percentage||double|True|
|wifiSignalStrength|**en**: Wi-Fi Signal Strength||double|True|
### Inherited Properties
* **[Equipment](../../Equipment.md):** operationalStageCount
* **[Asset](../../../Asset.md):** assetTag, commissioningDate, customProperties, customTags, identifiers, initialCost, installationDate, IPAddress, MACAddress, maintenanceInterval, modelNumber, name, serialNumber, turnoverDate, weight
* **[ICTEquipment](../ICTEquipment.md):** heightRUs, numberOfPorts, standard

---

## Target Of
### General
* [Portfolio](../../../../Collection/Portfolio.md).includes
* [PointOfInterest](../../../../Information/PointOfInterest.md).objectOfInterest
* [Agent](../../../../Agent/Agent.md).owns
* [Space](../../../../Space/Space.md).isLocationOf
* [Lease](../../../../Event/Lease.md).leaseOf
* [Point](../../../../Point/Point.md).isPointOf
* [Document](../../../../Information/Document/Document.md).documentTopic
* [Document](../../../../Information/Document/Document.md).url
* [ServiceObject](../../../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Architecture](../../../../Space/Architecture/Architecture.md).isFedBy
* [System](../../../../Collection/System/System.md).includes
* [Equipment](../../Equipment.md).feeds
* [Equipment](../../Equipment.md).isFedBy
* [Meter](../../Meter/Meter.md).meters
### Inherited
* [Loop](../../../../Collection/Loop/Loop.md).includes
* [Asset](../../../Asset.md).hasPart
* [Asset](../../../Asset.md).isPartOf
* [EquipmentCollection](../../../../Collection/Equipment-.md).includes
* [PointGroup](../../../../PointGroup.md).isPointGroupOf
