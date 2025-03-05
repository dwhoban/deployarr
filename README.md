# 🚀 Deployarr

> Transform your homelab setup from complex to click! Deployarr is your all-in-one solution for automated Docker-based homelab deployment.

[![Apps Supported](images/v5/Deployarr%20App%20Logos%20140.png)](APPS.md)

## 🌟 What is Deployarr?

Deployarr revolutionizes homelab setup by automating the deployment and configuration of Docker and Docker Compose environments. Whether you're a homelab enthusiast or a professional sysadmin, Deployarr streamlines the process of setting up and managing your containerized applications.

### 🎯 Key Features

- **Extensive App Support**: 140+ pre-configured applications ready for deployment
- **Intelligent Automation**: Automated environment setup with smart system checks
- **Enterprise-Grade Security**:
  - Socket-Proxy protection
  - CrowdSec integration
  - Multiple authentication options (Authentik, Authelia, Google OAuth)
- **Professional Networking**:
  - Advanced Traefik reverse proxy configuration
  - Flexible exposure modes (Internal, External, or Hybrid)
  - Multi-server and multi-domain support
- **Smart Management**:
  - Intuitive stack management interface
  - Automated backup and restoration
  - Comprehensive monitoring and logging

## 🚀 Quick Start

```bash
wget https://raw.githubusercontent.com/SimpleHomelab/deployarr/main/deployarr_v5.7.app
```

```bash
chmod +x deployarr_v5.7.app
```

```bash
./deployarr_v5.7.app
```

> 💡 For Raspberry Pi users, use the `-arm.app` version.

## 📊 Impact & Growth
![Deployarr Stats](images/v5/deployarr%20stats%20march%202025.png)

# 🧩 Supported Apps
Deployarr can automatically setup Socket Proxy, Traefik (fetch LE SSL certificates), Authentik, Authelia, Portainer, Plex, Jellyfin, Starr Apps, Gluetun, Dozzle, Uptime-Kuma, Homepage, CrowdSec, and other apps. 

[Full List of Apps](APPS.md)

## 🎓 Learn More

- 📚 [Official Documentation](https://www.simplehomelab.com/deployarr/)
- 🎥 [Quick Start Guide (20 min)](https://www.simplehomelab.com/go/deployarr-v5-intro/)
- 🎥 [Comprehensive Tutorial](https://www.simplehomelab.com/go/deployarr-v5-detailed-guide/)

## 💪 Supported Environments

- **Primary Platform**: Ubuntu and Debian-based systems
- **Deployment Options**: Baremetal, VM, Windows WSL, and LXC environments

## 🌟 License Options

Deployarr offers flexible licensing to suit different needs:

- **Free Tier**: Essential features for basic setups
- **Paid Tiers**: 
  - Basic
  - Plus
  - Pro
  
[View Detailed Comparison](https://www.simplehomelab.com/deployarr/pricing/)

> Annual [website memberships](https://www.simplehomelab.com/membership-account/join-the-geek-army/) include full Deployarr access!

## 🤝 Support & Community

Join our thriving community:
- [Deployarr Docs](https://docs.deployarr.app) - Answers to many common questions, fixes for issues, and improvement ideas
- [Discord Community](https://www.simplehomelab.com/discord/) - Get help and share experiences
- [YouTube Channel](https://www.youtube.com/@Simple-Homelab) - Tutorial videos and updates

## 🎯 Project Vision

Deployarr isn't just another container manager - it's your pathway to homelab mastery. Our goal is to:
- Simplify complex deployments
- Enable rapid testing and experimentation
- Foster learning through hands-on experience
- Provide quick recovery options when needed

## 📸 Feature Showcase

<details>
<summary>Click to view screenshots</summary>

#### Dashboard & Management
![Deployarr Dashboard](images/v5/11a%20Deployarr%20v5%20Deployarr%20Dashboard.png)
![Stack Manager](images/v5/13%20Deployarr%20v5%20Stack%20Manager.png)

#### Setup & Configuration
![System Checks](images/v5/02a%20system%20checks%20output.png)
![Security Options](images/v5/09%20Deployarr%20v5%20Security%20Options.png)

[View More Screenshots](#screenshots)
</details>

## 🔄 Known Limitations

- DNS Challenge Provider: Currently Cloudflare-only
- Port forwarding requirements: 80/443
- Specific database-dependent apps may require manual database removal

## 🌟 Contributing to Open Source

Part of Deployarr's revenue supports open-source projects through [OpenCollective](https://opencollective.com/deployarr).

---

<div align="center">

**Transform your homelab journey with Deployarr**

[Get Started](https://www.simplehomelab.com/deployarr/) | [Join Discord](https://www.simplehomelab.com/discord/) | [Watch Tutorial](https://www.simplehomelab.com/go/deployarr-v5-intro/)

</div>

