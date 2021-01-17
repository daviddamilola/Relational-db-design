**ER: entity relationship modelling**

*IDEF1X* notation is used in this course


Benefits

- relatively easy to understand
- hide/expose details when zooming in or out
- easy to convert to a logical db design

Risks
- wrong responsibility
- incomplete diagramatic techniques to capture all possible details discovered during work
- different notations



**Entity types**

Entity refers to objects, persons, events, abstractions, basically everything relevant in the context of the data application being designed.

objects, persons etc are referred to as *entity instances* or *instance*

entity instances for which the same kind of information is gathered are grouped together and called the **Entity type** or **Entity Class**

**Entity Type**
- describe all instances of the same type
- all instances have the same characteristics

In *IDEF1X* entity types are denoted by rectangle , horizontaly divided in the middle with the name of the entity type at the top

Entity types are meaningless without attributes

attributes are instance level facts about an entity occurrence.

each attribute is associated with exactly one entity type

Other attribute are placed below the dividing line

Key attribute are placed above the dividing line

Key attributes are used to identify a single occurrence in a group of similar entity occurences.

Key attributes that are formed from more than one attributes are called *Composite Keys*

an entity type can have a combination of attributes that can be used as keys, one is used as the primary key, the others are called alternate keys

**Relationships**

entites relate with each other at the instance level and at the abstracted class level

relationships is a class of facts that associate an instance of an entity type with another instance on an entity type

