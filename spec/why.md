# Why Connector Specification
This is the connection between the What and the various Why implementations.
By having the connections use the same label, it allows our UI to list all of the Whys associated with a What, independent of the Why's types.
Even if we don't have any UI to show a particular why, we can still show that there is a Why (and what the type is).

# Construction

// TODO add image?


# Why Connector Specification
Note that each implementation can store information in the Why Connector's properties.
The only restriction is that the implementation cannot use any of the reserved property keys (found below).

**Label** `Why`

**Reserved Properties**

* `Type` - The namespace of the Why (ie Note)