# ServiceNow Incident Automation Project

## Overview
This project enhances incident management in ServiceNow by integrating external employee data and improving workflow efficiency using core platform features.

## Features
- Import Sets & Transform Maps for automated data ingestion
- Dot Walking for dynamic data retrieval
- Dictionary Override for customized priority handling

## Implementation

### 1. Data Import
- Imported employee data using Import Sets
- Created Transform Map to populate `sys_user`

### 2. Dot Walking
- Retrieved:
  - Department
  - Email
  - Manager
- Used `assigned_to.field_name`

### 3. Dictionary Override
- Overrode default priority for custom Incident table
- Changed default from **4 (Low)** → **3 (Moderate)**

## Outcome
- Reduced manual data entry
- Improved data accuracy
- Enhanced incident resolution workflow

## Tech Used
- ServiceNow
- Import Sets
- Transform Maps
- Dictionary Override