# AWS <-> GCP HA-VPN (Terraform)

## Overview
Build a high-availability site-to-site VPN between AWS and GCP using BGP. Validate with instances on each side.

## Tech
AWS VGW/CGW, GCP HA VPN + Cloud Router, Terraform modules, BGP ASN plan.

## Steps
- Plan ASNs & linknets
- terraform apply for AWS side, then GCP side
- Verify BGP established; test connectivity

## Evidence
Add screenshots: BGP sessions up, traceroute, ping.