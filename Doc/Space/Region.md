[Index](../index.md) > [Space](Space.md) > [Region](#)
# Region

An administrative geospatial unit larger than the individual real estate. For instance, "Lombary", "North America", "The Back Bay", "Elnätsområde Syd", etc.


**Display name:** Region<br />
**DTMI:** dtmi:org:w3id:rec:Region;1

---

## Relationships

### Inherited Relationships
* **[Space](Space.md):** geometry, georeference, hasPart, isLocationOf, isPartOf

---

## Properties

### Inherited Properties
* **[Space](Space.md):** customProperties, customTags, identifiers, name

---

## Target Of
### General
* [Portfolio](../Collection/Portfolio.md).includes
* [PointOfInterest](../Information/PointOfInterest.md).objectOfInterest
* [Agent](../Agent/Agent.md).owns
* [Space](Space.md).isLocationOf
* [Lease](../Event/Lease.md).leaseOf
* [Point](../Point/Point.md).isPointOf
* [Document](../Information/Document/Document.md).documentTopic
* [Document](../Information/Document/Document.md).url
* [ServiceObject](../Information/ServiceObject/ServiceObject.md).relatedTo
* [Architecture](Architecture/Architecture.md).isFedBy
* [System](../Collection/System/System.md).includes
* [Equipment](../Asset/Equipment/Equipment.md).feeds
* [Equipment](../Asset/Equipment/Equipment.md).isFedBy
* [Meter](../Asset/Equipment/Meter/Meter.md).meters
### Inherited
* [Asset](../Asset/Asset.md).locatedIn
* [LogicalDevice](../LogicalDevice/LogicalDevice.md).locatedIn
* [PointGroup](../PointGroup.md).locatedIn
* [Space](Space.md).hasPart
* [Space](Space.md).isPartOf
* [SpaceCollection](../Collection/Space-.md).includes
