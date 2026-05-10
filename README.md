# Custom FreeRADIUS 4.0

Customized FreeRADIUS 4.0 package with GUI support for ISP deployments.

## Package details

- **Built for:** Ubuntu 24.04 LTS x86_64
- **Includes:** FreeRADIUS 4.0 with GUI
- **Database support:** PostgreSQL and MySQL
- **Maintainer:** Oguz Ersoz  
  Email: info@dahili.net  
  Phone: +90 554 884 28 14

## Download

GitHub cannot host the 435 MB package in this repository. Download the package from SourceForge:

https://sourceforge.net/projects/custom-freeradius/

## Installation

1. SSH into your Ubuntu 24.04 LTS x86_64 server.
2. Download the `freeradius-custom-4.0` package from https://sourceforge.net/projects/custom-freeradius/
3. If the download page provides a SHA256 checksum, verify the package before installing it:

   ```bash
   sha256sum ./freeradius-custom-4.0*.deb
   ```

   Compare the output with the checksum published on the download page.
4. Install the downloaded package:

   ```bash
   sudo dpkg -i ./freeradius-custom-4.0*.deb
   ```

5. If `dpkg` reports missing dependencies, run:

   ```bash
   sudo apt-get install -f
   ```
