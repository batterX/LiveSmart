# batterX Live & Smart (v17.11.27-fix)

## Update Monitoring App

### Version Specific Requirements

Before Updating please see if there are any `Version Specific Requirements` that need to be done

#### v18.1.11
Open `Terminal` and run command `$ sudo apt-get install sseclient-py`

### One-Click Update

Navigate to `http://YOUR_RASPI_IP_ADDRESS/service`

Click the `Update` icon (enter the correct password, if prompted)

Click `OK` to confirm that the System should be updated

After the update the Raspberry Pi will automatically reboot and apply the new version

### Manual Update:

If for some reason it is not possible to update the software using the Local Web App

Login to your Raspberry Pi using `Remote Desktop Connection` or directly using an HDMI display

Open Raspberry Pi's `File Manager` and navigate to `/home/pi`

Double-click on `updater.sh` and click `Execute in Terminal`

After the update the Raspberry Pi will automatically reboot and apply the new version.