# Splunk add-on for IDE Studio: releases

Releases and issue reports for the Splunk add-on for IDE Studio, a macOS development
environment. The add-on brings everything IDE Studio does for Splunk:

- Project templates: Splunk App with Dashboards, Technology Add-on, Technology Add-on (UCC),
  Blank App, Custom Search Command, Custom REST Endpoint, Custom Alert Action, Blank SPL Project
- Completion, help and checks for SPL and Splunk `.conf` files (a language server)
- Build (checks and packaging), Run in a test Splunk (a Docker container, or your own Splunk),
  AppInspect, Splunk's tools, Run Search, and debugging an app's Python scripts

## Installing

Download the `.zip` from the [latest release](../../releases/latest), then in IDE Studio choose
**IDE Studio › Add-ons… › Install from File…**. Opening a Splunk project without the add-on also
offers **Download and Install**.

The add-on includes a program (`splunk-studio`, for Apple silicon and Intel Macs). IDE Studio
shows it and asks before installing.

## Updates

IDE Studio checks this repository's latest release at most once a day and whenever the Add-ons
window opens, and offers a newer version with an **Update** button. Each download is checked
against the checksum in the release's `updates.json`, and nothing is installed without a click.

## Reporting a problem

Open an [issue](../../issues) with the add-on's version (shown in the Add-ons window), what you
did, and what the console showed.
