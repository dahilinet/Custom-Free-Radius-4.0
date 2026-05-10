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
2. Download the `freeradius-custom-4.0` package from the SourceForge link above.
3. Install the downloaded package:

   ```bash
   sudo dpkg -i ./freeradius-custom-4.0*.deb
   ```

4. If `dpkg` reports missing dependencies, run:

   ```bash
   sudo apt-get install -f
   ```
