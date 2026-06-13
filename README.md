<div align="center">

# Hi, I'm Daniel 👋

**Infrastructure Engineer** | Endpoint Management | Automation | ML Infrastructure

</div>

---

🔧 **What I Do**

I build and manage production infrastructure — from Microsoft 365 and Azure to NixOS and Talos Linux. Most of my work can't go on GitHub in its original form, so what you see here is largely general purpose templates and a few automation tools I have created.

📡 **Microsoft 365 & Endpoint Management**
- Intune policy design and deployment (Windows + macOS)
- SharePoint tenant-to-tenant migrations with certificate-based auth
- Entra ID app registration, DPAPI encryption, PnP PowerShell automation
- Endpoint hardening: Tamper Protection, Firewall, Local Admin, Folder Redirection

🐧 **Linux Infrastructure**
- NixOS with Flakes, Home Manager, sops-nix, and Comin auto-deploy — managed declaratively
- Ansible automation for Linux servers, hypervisors, and MikroTik routers
- Docker, SSH key management, log hygiene
- Talos Linux and KubeVirt for pod/VM management

🛠️ **Tooling**

`C#` `PowerShell` `Nix` `Ansible` `YAML` `JSON` `Bash`

`NixOS` `WSL2` `XCP-NG` `MikroTik RouterOS` `Intune` `Entra ID` `SharePoint`

`PnP PowerShell` `sops-nix` `Home Manager` `Git` `Delta` `Talos Linux`

---

📁 **Repositories**

| Repo | What It Is |
|------|-----------|
| [**Tenant2Tenant-Migration-Tool**](https://github.com/WalterLuigi/Tenant2Tenant-Migration-Tool) | C# WPF + PowerShell app for migrating SharePoint sites between Microsoft 365 tenants. Dry-run preview, certificate-based auth, automated bootstrapping/teardown, and a GUI. |
| [**Intune-Templates**](https://github.com/WalterLuigi/Intune-Templates) | 17 ready-to-import Intune policy templates (Windows + macOS) exported as Graph API JSON. |
| [**WSL-NixOS-Config**](https://github.com/WalterLuigi/WSL-NixOS-Config) | Declarative NixOS WSL setup with Flakes, sops-nix, Home Manager, Comin, and Delta. Sanitized version of my daily driver when using Windows. |
| [**Ansible-Scripts**](https://github.com/WalterLuigi/Ansible-Scripts) | Ansible playbooks for MikroTik routers, Linux servers, hypervisors, and Docker. |

---

⚠️ **A Note on Sanitization**

My repos contain `YOUR_*_HERE` and `{REPLACE ME WITH *}` placeholders because the real configs include tenant IDs, hostnames, and internal URLs that will vary based on your environment. The Intune policies are general purpose and will require variable substituion to fit your environment in some cases.

<div align="center">

---

</div>
