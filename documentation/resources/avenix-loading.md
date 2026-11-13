---
description: "Installation, configuration, and troubleshooting guide for the Avenix Loading FiveM resource."
icon: loader
---

# Avenix Loading

Welcome to the official documentation for **Avenix Loading** by Avenix Studios.

This page is the central guide for installing, configuring, and maintaining Avenix Loading.

{% hint style="warning" %}
This is the initial documentation structure. Resource-specific technical details still need to be confirmed against the actual release files so that the instructions are accurate.
{% endhint %}

## Overview

**What it does:** Add the confirmed description of Avenix Loading here.

**Current version:** Add the released version here.

**Supported frameworks:** Confirm whether this resource is standalone or requires a framework.

## Requirements

List every required dependency and its minimum supported version.

| Dependency | Required version | Notes |
|---|---|---|
| To be confirmed | — | Confirm from the resource's `fxmanifest.lua` and release package |

## Installation

{% stepper %}
{% step %}
### Download the resource

Download Avenix Loading from the official Avenix Studios release or Tebex product page.
{% endstep %}
{% step %}
### Add it to your server

Place the resource folder in your server's resources directory. Keep the resource folder name unchanged unless the release instructions say otherwise.
{% endstep %}
{% step %}
### Configure the resource

Open the resource configuration file and apply the settings described in the Configuration section below. Exact file names and options need to be added from the current release.
{% endstep %}
{% step %}
### Start the resource

Add the correct `ensure` entry to your server configuration, then restart the server and check the console for errors.
{% endstep %}
{% endstepper %}

## Configuration

Document each setting using this format:

| Setting | Default | Description |
|---|---|---|
| To be confirmed | — | Add the exact option name and behavior from the shipped config |

Do not copy example values into your live server without checking the configuration shipped with your version.

## Commands and permissions

Add the exact player/admin commands and permission requirements here. If the resource has no commands or permission checks, state that explicitly.

## Troubleshooting

| Problem | What to check |
|---|---|
| Resource does not start | Check the server console, resource folder name, and required dependencies |
| UI or loading screen does not appear | Check the client F8 console, NUI asset paths, and the resource start order |
| Missing files or assets | Confirm that the release package was extracted completely and that the paths in `fxmanifest.lua` match the files |

## Changelog

Add release notes here, newest version first.

---

## Documentation checklist

Before publishing the final version of this page, confirm:

- [ ] Exact resource version
- [ ] Dependencies and supported frameworks
- [ ] Correct installation steps and resource start name
- [ ] All configuration options and their defaults
- [ ] Commands, permissions, and exports (if any)
- [ ] Screenshots or a short setup video
- [ ] Known issues and support instructions
