[Index](../../index.md) > [Information](../Information.md) > [Georeference](Georeference.md) > [Geotransform](#)
# Geotransform

A transform following GDAL's Affine Transform that transforms a local coordinate into a WGS84 coordinate. Created from Ground Control Points (GCP) using GDAL's GCPsToGeotransform method.


**Display name:** Geotransform<br />
**DTMI:** dtmi:org:w3id:rec:Geotransform;1

---

## Properties

|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|heightScaleFactor|**en**: height scale factor||double|True|
|originX|**en**: origin x||double|True|
|originY|**en**: origin y||double|True|
|widthScaleFactor|**en**: width scale factor||double|True|
|xRotationalScaleFactor|**en**: x rotational scale factor|**en**: Value will be zero if the local coordinate system is north-aligned.|double|True|
|yRotationalScaleFactor|**en**: y rotational scale factor|**en**: Value will be zero if the local coordinate system is north-aligned.|double|True|
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
### Inherited
* [Space](../../Space/Space.md).georeference
