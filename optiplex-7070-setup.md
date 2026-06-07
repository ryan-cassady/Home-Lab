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
- [ ] All Windows updates installed
- [ ] System restarted and confirmed up to date

### Phase 2 — Clean
- [ ] Export installed apps list via PowerShell
- [ ] Remove bloatware and unnecessary apps
- [ ] Clean up startup programs
- [ ] Disable unnecessary background services

### Phase 3 — Secure
- [ ] Install Bitwarden password manager
- [ ] Set strong PIN/password
- [ ] Configure Windows Defender
- [ ] Configure Windows Firewall
- [ ] Enable BitLocker

### Phase 4 — Configure
- [ ] Enable Remote Desktop (RDP)
- [ ] Set static IP address
- [ ] Configure power settings (never sleep)
- [ ] Test Remote Desktop from Surface Book 3
- [ ] Ditch monitor — confirm headless operation

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
