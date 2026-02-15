# Project 01: Secure VNet + NSGs

## Goal
Build a secure VNet with subnets and NSG rules that follow least privilege.

## What I will build
- VNet with 2 subnets (Admin, App)
- NSG rules
  - Allow admin only from my IP
  - Deny everything else by default

## Evidence to include
- Screenshots of VNet, subnets, NSG rules
- Notes explaining why each rule exists

## Build checklist
- [ ] Create Resource Group
- [ ] Create VNet
- [ ] Create subnets: Admin, App
- [ ] Create NSG for Admin subnet
- [ ] Add rule: allow SSH or RDP only from my IP
- [ ] Create NSG for App subnet
- [ ] Add rules: only required inbound, deny rest
- [ ] Screenshot evidence and upload to repo
