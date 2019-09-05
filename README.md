# Octoprint-Install-Script
An installation script to install Octoprint on Raspbian Stretch. Can optionally install and configure all of the following for complete working setup with touchscreen support:

* **OctoPrint** -- install Octoprint from latest source
* **HAProxy** -- install and configure to proxy everything through port 80
* **Enable_GL** -- Enable Hardware Acceleration *(Only tested with Rpi3 on Stretch)*
* **LCD Portrait Rotation** -- Configure LCD for Portrait Mode *(Only tested with Official 7" LCD Touchscreen)*
* **TouchUI** -- Installs and configured TouchUI and automatic startup directly in to X (No Desktop)
* **Custom BootSplash** -- Configures a custom animated boot screen
* **Samba/Bonjour** -- Allows LAN access to Octoprint by hostname

## To use:
On a fresh installation on Raspbian Stretch, retrieve and run the install shell script.

```bash
sudo bash -c "apt-get update && apt-get install curl -y && curl -s https://raw.githubusercontent.com/bradcarnage/Octoprint-Install-Script/proxmox-ubuntu-ct/octoprint_setup.sh | bash -s"
```
