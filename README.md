# openrgb_gbx57_mobo_fix_popos
openrgb gigabyte x570 corsair vengence rgb pro smbus fix

Quick fix for OpenRGB Access to RAM on Gigabyte X570 platforms running pop_os.

sudo apt install i2c-tools -y

sudo modprobe i2c-dev

sudo modprobe i2c-piix4

sudo kernelstub -a "acpi_enforce_resources=lax"

Reboot
