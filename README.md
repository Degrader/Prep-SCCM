Preps server for SCCM Installation/Deployment. Installs necessary roles and features for SCCM, as well as configuring firewall rules for these roles/features. Creates Sources directory and subdirectories on D: data volume, adds Domain Admins with inherited Full Control to top level directory. Sources directory contains Applications, OSD, Packages directories. OSD directory contains Drivers and Images directories.

A version of this script without the "Sources" directory is available here https://github.com/Degrader/Prep-SCCM-DP if you don't want to just comment out or delete that bit in this script.
