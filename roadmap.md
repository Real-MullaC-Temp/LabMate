# 🗺️ LabMate Roadmap

LabMate is a cross-platform, open-source toolbox for configuring Cisco routers and switches.  
The goal: make network device setup **simple, fast, and approachable** for CCNA students, homelabbers, and small IT teams — with no installation or admin rights required.

---

## ✅ v0.1.0 — MVP (First Public Release)

- [ ] **Single Device Support**
- [ ] **Connect via SSH**
- [ ] Prompt for IP, username, password
- [ ] Run `show ip int brief` and display output
- [ ] Rich console output for better readability
- [ ] Build standalone executable with **PyInstaller**
- [ ] Add **Textual TUI** with tabbed layout:
  - [ ] CLI Tab (manual commands)
  - [ ] Interfaces Tab (view & configure interfaces)
- [ ] Persistent device profile (save host/username locally)
- [ ] Show commands being executed in bottom console log
- [ ] Basic error handling for wrong login / timeout
- [ ] Provide prebuilt binaries for Windows, Linux, macOS

---

## 🔐 v0.2.0 — ACL Management

- [ ] Add **ACL Tab**:
  - List existing ACLs
  - Add simple standard ACL entries
  - Apply ACLs to interfaces
- [ ] Dry-run preview before applying config changes
- [ ] Configuration rollback (capture running config before change)

---

## 🧰 v0.3.0 — Usability & Polish

- [ ] Keyboard navigation & hotkeys
- [ ] Search/filter for interfaces & ACLs
- [ ] Clear, actionable error messages
- [ ] Export device data to JSON/YAML
- [ ] Optional guided setup for lab environments

---

## 🌐 v0.4.0 — Beyond Single Device

- [ ] Multi-device support (switch between devices in tabs)
- [ ] Bulk interface changes
- [ ] Config diff view (compare running configs between devices)

---

## 📅 Future Ideas

- Telnet & Serial Console Support (via PySerial)
- VLAN configuration wizard
- Auto-generate basic router/switch config templates
- Backup & restore configs locally
- Plugin system for other vendors (Juniper, HP, MikroTik)
- CI/CD pipeline to auto-build EXEs for every tagged release
- Theme switcher (dark/light mode)

---

## 🏁 Project Goal

Make LabMate a **fast, intuitive, cross-platform utility**  
that helps anyone — from students to network engineers — configure Cisco devices with confidence.

