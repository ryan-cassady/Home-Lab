# Dell OptiPlex 7070 Micro — Server Setup

## Setup Protocol
Patch → Clean → Secure → Configure → Install

---

## Hardware Specs
- CPU: Intel Core i7-9700T (8 cores)
- RAM: 16GB DDR4 2666MHz
- Storage: 256GB NVMe SSD
- Network: Gigabit Ethernet + WiFi 5 (802.11ac)
- OS: Windows 11 Pro

---

## Setup Checklist

### Phase 1 — Patch
- [x] Initial Windows setup completed
- [x] Windows activation confirmed
- [x] All Windows updates installed
- [x] System restarted and confirmed up to date

### Phase 2 — Clean
- [x] Export installed apps list via PowerShell
- [x] Remove bloatware and unnecessary apps
- [x] Clean up startup programs
- [x] Disable unnecessary background services

### Phase 3 — Secure
- [x] Install Bitwarden password manager
- [x] Set strong PIN/password
- [x] Configure Windows Defender
- [x] Configure Windows Firewall
- [x] Enable BitLocker

### Phase 4 — Configure
- [x] Enable Remote Desktop (RDP)
- [x] Set static IP address
- [x] Configure power settings (never sleep)
- [x] Test Remote Desktop from Surface Book 3
- [x] Ditch monitor — confirm headless operation

### Phase 5 — Install
- [ ] Install Chrome
- [ ] Install VirtualBox
- [ ] Install Jellyfin
- [ ] Install 7-Zip
- [ ] Install VLC

---

## Notes
- Server runs headless after Phase 4
- Accessed remotely via RDP from Surface Book 3
- Date started: June 2026
