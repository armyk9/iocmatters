
# ArmyK9's Thunderbird Plugins
# ipmatters & hashmatters

Welcome to **ipmatters** and **hashmatters** — two plugins designed to enhance your email security capabilities within the Thunderbird email client. These tools streamline processes for identifying and blacklisting malicious IP addresses and generating file hashes of suspicious attachments.

## Overview

- **ipmatters**: Extracts the source IP address from an email header and saves it into a blacklist file.
- **hashmatters**: Generates a SHA256 hash of any downloaded attachment to help block further matches of malicious files.

---

## ipmatters

**ipmatters** is a lightweight plugin that helps with the identification of suspicious email senders by extracting the source IP from an email header and saving it in a blacklist.

### Features:
- Right-click on any email to extract the source IP address.
- Automatically saves the IP to `ip-blacklist.txt` on your desktop for easy access.
- Ideal for enhancing email security by quickly identifying and blocking malicious IPs.

---

## hashmatters

**hashmatters** simplifies threat intelligence by allowing users to hash email attachments and block suspicious files from spreading.

### Features:
- Right-click on any downloaded attachment (e.g., PDF, Excel) within Thunderbird.
- Generates a SHA256 hash of the file, saving it to `ioc.txt` on your desktop.
- Use this hash in endpoint security or antivirus systems to block files with matching hashes, aiding in incident response.

---

## Installation

### Step-by-Step Instructions:

1. **Clone the Repository**:
   - Clone the repository by running the following command in your terminal or command prompt:
   
   ```bash
   git clone https://github.com/armyk9/iocmatters.git
   ```

2. **Install the Plugins in Thunderbird**:
   - Open Thunderbird and click on **Tools** in the top menu bar.
   - Select **Add-ons and Themes**.
   - Click on the settings icon (cogwheel) in the Add-ons Manager and choose **Install Add-on From File**.
   - Locate the `.zip` files for **ipmatters** and **hashmatters**, and select them to install directly.

3. **Restart Thunderbird**:
   - Once the installation is complete, restart Thunderbird to apply the changes.

---

## How to Use

- **ipmatters**: Right-click any email, extract the source IP address from the header, and add it to the `ip-blacklist.txt` on your desktop.
- **hashmatters**: Right-click on any downloaded attachment, generate a SHA256 hash, and save it in the `ioc.txt` file on your desktop.

---

## Contribution

Feel free to contribute by forking the project and submitting pull requests for new features or improvements.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact

For questions or support, reach out through the GitHub repository or via email.
