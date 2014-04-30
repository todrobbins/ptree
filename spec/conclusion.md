# Conclusion Specification
An abstract concept encompassing Events, Facts, Relationships, etc..

Note: This pulls heavlily from the following GEDCOMX specs:
> https://github.com/FamilySearch/gedcomx/blob/master/specifications/event-types-specification.md
> https://github.com/FamilySearch/gedcomx/blob/master/specifications/fact-types-specification.md
> https://familysearch.org/developers/docs/guides/facts


# TODO
> Decide if conclusion types can point to other conclusion types (which is dangerous). Leaning toward no right now.

# Conclusion Types

* [name](name.md) - A representation of a person's name, in all of its complexity and glory.
* [marriage](marriage.md) - We are gathered here today...
* [birth](birth.md) - Everyone has one.
* [gender](gender.md) - Everyone has one.

# Contributing Conclusion Types
Fork and submit a pull request. Just be kind while playing in the global namespace :)

# Custom Conclusion Types
When you don't want to contribute your custom conclusion type, just go ahead and use it. It won't break anything.
Please follow the conventions and namespace them (ie `mycompany_type_subtype`) to avoid collisions.
And remember that conclusions are "Whats", not "Whys".

# Conventions

> Every conclusion has a root Node whose label typically is the name of the conclusion, Camel Cased.

> Every Conclusion Relationship label typically takes the form of `<type>_<sub type?>_Ref`