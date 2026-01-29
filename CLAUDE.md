# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This repository contains static resources for UIB (User Interface Builder) demos. It is a data-only repository with no executable code or build processes. Resources are meant to be accessed via direct URLs for use in demos and applications.

## Repository Structure

- `logo/` - Brand assets (CNAF logo in JPEG format)
- `sample-data/` - JSON data files containing sample telecom products and services

## Accessing Resources via URL

Resources in this repository can be accessed directly via GitHub raw URLs:

```
https://raw.githubusercontent.com/bonitasoft-presales/uib_resources/main/<path-to-file>
```

Examples:
- Logo: `https://raw.githubusercontent.com/bonitasoft-presales/uib_resources/main/logo/logo-cnaf.jpg`
- Product data: `https://raw.githubusercontent.com/bonitasoft-presales/uib_resources/main/sample-data/telecom-products.json`

These URLs can be used directly in applications, demos, or UIB configurations to reference static assets and data.

## Sample Data Format

The `sample-data/telecom-products.json` file contains an array of telecom products with the following structure:
- Each product has an EAN13 identifier
- Products are categorized by type: `hardware`, `software`, or `service`
- Hardware/software products include: name, category, brand, price, features
- Service products include: name, category, provider, price, billing period, features

Product types include networking hardware, cabling, telephony equipment, wireless infrastructure, software platforms, and consumer/enterprise services.

## License

This repository is licensed under Apache License 2.0.
