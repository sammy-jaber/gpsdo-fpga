# GPSDO FPGA

VHDL design for a GPS disciplined oscillator (GPSDO). A GNSS receiver's
pulse-per-second signal is used to steer a 10 MHz OCXO, giving a stable,
accurate 10 MHz reference and a 1 PPS output aligned to GPS time.

All timing, measurement and control logic runs in the FPGA, written entirely
in VHDL with no soft-core CPU.

Project page: https://www.sammyjaber.co.uk/projects/GPS%20Disciplined%20Oscillator/GPS%20Disciplined%20Oscillator.html
