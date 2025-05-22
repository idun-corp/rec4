[Index](../../../index.md) > [Space](../../Space.md) > [Architecture](../Architecture.md) > [Room](Room.md) > [Hallway](#)
# Hallway

**Display name:** Hallway<br />
**DTMI:** dtmi:org:w3id:rec:Hallway;1

---

## Components

### Inherited Components
* **[Architecture](../Architecture.md):** area, capacity

---

## Relationships

### Inherited Relationships
* **[Architecture](../Architecture.md):** address, adjacentElement, architectedBy, constructedBy, containsElement, documentation, hasPoint, intersectingElement, isFedBy, operatedBy, ownedBy
* **[Space](../../Space.md):** geometry, georeference, hasPart, isLocationOf, isPartOf

---

## Properties

### Inherited Properties
* **[Space](../../Space.md):** customProperties, customTags, identifiers, name

---

## Target Of
### General
* [Portfolio](../../../Collection/Portfolio.md).includes
* [PointOfInterest](../../../Information/PointOfInterest.md).objectOfInterest
* [Agent](../../../Agent/Agent.md).owns
* [Space](../../Space.md).isLocationOf
* [Lease](../../../Event/Lease.md).leaseOf
* [Point](../../../Point/Point.md).isPointOf
* [Document](../../../Information/Document/Document.md).documentTopic
* [Document](../../../Information/Document/Document.md).url
* [ServiceObject](../../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Architecture](../Architecture.md).isFedBy
* [System](../../../Collection/System/System.md).includes
* [Equipment](../../../Asset/Equipment/Equipment.md).feeds
* [Equipment](../../../Asset/Equipment/Equipment.md).isFedBy
* [Meter](../../../Asset/Equipment/Meter/Meter.md).meters
### Inherited
* [Point](../../../Point/Point.md).locatedIn
* [Apartment](../../../Collection/Apartment.md).includes
* [Asset](../../../Asset/Asset.md).locatedIn
* [BuildingElement](../../../BuildingElement/BuildingElement.md).locatedIn
* [Campus](../../../Collection/Campus.md).includes
* [LogicalDevice](../../../LogicalDevice/LogicalDevice.md).locatedIn
* [PointGroup](../../../PointGroup.md).locatedIn
* [Premises](../../../Collection/Premises.md).includes
* [RealEstate](../../../Collection/RealEstate.md).includes
* [Space](../../Space.md).hasPart
* [Space](../../Space.md).isPartOf
* [SpaceCollection](../../../Collection/Space-.md).includes
