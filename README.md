# KQL Security Detections

This repository contains production-ready KQL queries for:

- Microsoft Sentinel
- Microsoft Defender for Endpoint / XDR

## Purpose
- Detection engineering
- Threat hunting
- Incident response

## Folder Structure

- `detections/endpoint/` : Production-grade endpoint detections
- `detections/identity/` : Identity-related detections (future)
- `detections/cloud/` : Cloud platform detections (future)
- `helpers/` : Reusable KQL snippets
- `sentinel-analytic-rules/` : Exported rule JSONs (optional)

## Disclaimer
Queries are provided as-is. Test and tune thresholds before production use. False positives may occur depending on environment.
