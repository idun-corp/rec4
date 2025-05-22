[Index](../../index.md) > [Information](../Information.md) > [Geometry](#)
# Geometry

**Display name:** Geometry<br />
**DTMI:** dtmi:org:w3id:rec:Geometry;1

---

## Child interfaces
* [MultiPoint](MultiPoint.md)
* [MultiPolygon](MultiPolygon.md)
* [Point](Point.md)
* [Polygon](Polygon.md)

---

## Properties

|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|coordinateSystem|**en**: coordinate system||enum (LocalCoordinates, SWEREF99, WGS84)|True|
### Inherited Properties
* **[Information](../Information.md):** customProperties, customTags, identifiers, name

---

## Target Of
### General
* [Portfolio](../../Collection/Portfolio.md).includes
* [PointOfInterest](../PointOfInterest.md).objectOfInterest
* [Agent](../../Agent/Agent.md).owns
* [Space](../../Space/Space.md).isLocationOf
* [Lease](../../Event/Lease.md).leaseOf
* [Point](../../Point/Point.md).isPointOf
* [Document](../Document/Document.md).documentTopic
* [Document](../Document/Document.md).url
* [ServiceObject](../ServiceObject/ServiceObject.md).relatedTo
* [Architecture](../../Space/Architecture/Architecture.md).isFedBy
* [System](../../Collection/System/System.md).includes
* [Equipment](../../Asset/Equipment/Equipment.md).feeds
* [Equipment](../../Asset/Equipment/Equipment.md).isFedBy
* [Meter](../../Asset/Equipment/Meter/Meter.md).meters
### Direct
* [Asset](../../Asset/Asset.md).geometry
* [Space](../../Space/Space.md).geometry
