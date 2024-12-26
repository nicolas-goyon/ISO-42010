# Correspondence rule

In [ADs](Architecture_Description.md), one consequence of employing multiple [views](Architecture_View.md), and many architects is the needs to express and maintain **consistency** between those architects, the [AD elements](Architecture_Description_Element.md), their [relationshipts](Correspondence.md) and [views](Architecture_View.md).

Correspondence rules are used to enforce [relations](Correspondence.md) within an [architecture description](Architecture_Description.md). A correspondence rule **holds** if an associated [correspondence](Correspondence.md) can be shown to satisfy the rule. A correspondence rule is **violated** if an associated [correspondence](Correspondence.md) can be shown not to satisfy the rule or when no associated [correspondence](Correspondence.md) exists.

Requirement : An [architecture description](Architecture_Description.md) shall include each **correspondence rule** applying to it.
