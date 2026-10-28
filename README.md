# Enterprise Virtualization Home Lab

A personal lab on a Dell PowerEdge R630 where I practice network administration, virtualization, security, and local AI deployment.

## Hardware

- Dell PowerEdge R630 running Proxmox VE
- NVIDIA Tesla P4 GPU, passed through to a VM for local LLM workloads
- Ender 3 and Ender 3 S1 3D printers running Klipper, used for custom server cooling and mounting parts

## Virtualization and services

- Proxmox VE hosting virtual machines and LXC containers
- Pi-hole for network-wide DNS filtering and internal DNS
- Nginx Proxy Manager for reverse proxy and SSL termination
- HedgeDoc (Docker, in an LXC container) for self-hosted markdown notes, published through the reverse proxy
- Ollama and Open WebUI for a private local AI environment
- Private AzerothCore and Palworld game servers, for practice with backend databases and network access

## Network and security

- VLAN segmentation separating management, IoT, and production services
- Ongoing monitoring of server temperatures and service uptime

## Tools

Proxmox VE, Docker, LXC, Linux, Pi-hole, Nginx Proxy Manager, Ollama, VLANs
