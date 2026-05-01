# NOVUS-OS Matrices
![NOVUS-OS Banner](ссылка_на_красивую_картинку_с_логотипом)

Official service matrices and game server configurations for NOVUS-OS.

## Repository Role
Public source of official JSON and YAML matrix definitions for game and service provisioning.

## Delivery Model
Matrices are versioned directly in this public repository.
NOVUS-OS Panel imports them into novus_os and validates updates on a weekly schedule.

## Integration
Primary sync endpoint in panel: /api/matrices/sync.

## Security
Never store credentials or secrets inside matrix files.

## License
See LICENSE in this repository.
