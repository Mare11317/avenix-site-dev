---
description: Overview of Avenix Core and its role in shared resource integrations.
---

# Avenix Core

Avenix Core is intended to provide shared functionality for Avenix resources and help integrations stay consistent across supported server setups.

## Integration principles

* Use API documentation shipped with the exact installed version.
* Confirm the configured framework and bridge before connecting another resource.
* Start required dependencies before dependent resources.
* Keep permission checks on the server.
* Review console output when an integration cannot initialize.

## API reference status

This is an overview, not a complete export reference. Exact export names, parameters, return values, framework support, and inventory or money methods must be documented from the current avenix\_core source and release.

{% hint style="warning" %}
Never assume an export exists because another resource uses a similarly named function. Verify it against the installed Avenix Core version.
{% endhint %}
