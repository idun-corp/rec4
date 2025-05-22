[Index](index.md) > [PointGroup](#)
# PointGroup

**Display name:** Point Group<br />
**DTMI:** dtmi:org:w3id:rec:PointGroup;1

---

## Relationships

|Name|Display name|Description|Multiplicity|Target|Properties|Writable|
|-|-|-|-|-|-|-|
|hasMember|**en**: has member||0-Infinity|[Point](Point/Point.md)||True|
|isPointGroupOf|**en**: is point group of||0-Infinity|[Asset](Asset/Asset.md)||True|
|locatedIn|**en**: located in||0-1|[Space](Space/Space.md)||True|

---

## Properties

|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|customTags|**en**: Custom Tags||map (string->boolean)|True|
|identifiers|**en**: Identifiers||map (string->string)|True|
|name|**en**: name||string|True|

---

## Target Of
### General
* [Portfolio](Collection/Portfolio.md).includes
* [PointOfInterest](Information/PointOfInterest.md).objectOfInterest
* [Agent](Agent/Agent.md).owns
* [Space](Space/Space.md).isLocationOf
* [Lease](Event/Lease.md).leaseOf
* [Point](Point/Point.md).isPointOf
* [Document](Information/Document/Document.md).documentTopic
* [Document](Information/Document/Document.md).url
* [ServiceObject](Information/ServiceObject/ServiceObject.md).relatedTo
* [Architecture](Space/Architecture/Architecture.md).isFedBy
* [System](Collection/System/System.md).includes
* [Equipment](Asset/Equipment/Equipment.md).feeds
* [Equipment](Asset/Equipment/Equipment.md).isFedBy
* [Meter](Asset/Equipment/Meter/Meter.md).meters
### Direct
* [Point](Point/Point.md).isMemberOf
