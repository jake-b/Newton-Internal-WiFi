# Newton-Internal-WiFi
Design and software for a WiFi board for the Apple Newton MessagePad 2x00

- The PCB design for the board (v1.1)
- The Newton PKG software module for enabling the board in software
- STL files for 3D printing a replacement modem port cover. The original
  port cover interferes with the installed PCB.  I have also included a
  representation of the original port cover, in case you need one.  There
  is a version with supports for printing on a typical hobbiest 
  fused-filament 3D printer.  Trim carefully to size using a razor blade.

# Bill of Materials

- PCB fabricated to 0.8mm thickness
- IW-SMG2SMT-EX - Wireach WiFi / 802.11 Module - External Antenna
- JAE IL-WX-32PB-VF-BE - Internal Connector - No longer available
- LMZ21700SILT - Voltage Regulator Module
- R1 SMD 0603 15k Resistor
- Cout SMD 0805 22uF Capacitor
- Cin, C3 SMD 0805 10uF Capacitor
- Css SMD 0603 3.3nF Capacitor
- C4 SMD 0805 470nF
- Rt SMD 0603 562K ohm 1% Resistor
- Rb SMD 0603 180Kohm 0.5% Resistor
- MC74VHCT50ADT - Buffer
- MC74VHC1G04DFT2G - 1G Inverter
- Resettable Fuses - PPTC 15V 1206 .500A POLYFUSE

# License & Disclaimer
This project is released under the Attribution-NonCommercial-ShareAlike 4.0 
International license.

- Feel free to make your own, or make one for your friends.
- Please release any improvements back to the community.
- Non-commerical use only. Please don't make & sell these at a profit.  If
  by some odd chance you want to make these for sale, please contact me.

As with all of my projects, please use this at your own risk.

BECAUSE THE PROGRAM & HARDWARE DESIGN IS LICENSED FREE OF CHARGE, THERE IS NO 
WARRANTY FOR THE PROGRAM & HARDWARE DESIGN, TO THE EXTENT PERMITTED BY 
APPLICABLE LAW. EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT HOLDERS 
AND/OR OTHER PARTIES PROVIDE THE PROGRAM & HARDWARE DESIGN "AS IS" WITHOUT 
WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED 
TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR 
PURPOSE. THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE PROGRAM &
HARDWARE DESIGN IS WITH YOU. SHOULD THE PROGRAM OR HARDWARE DESIGN PROVE 
DEFECTIVE, YOU ASSUME THE COST OF ALL NECESSARY SERVICING, REPAIR OR CORRECTION.

IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING WILL ANY
COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MAY MODIFY AND/OR REDISTRIBUTE THE 
PROGRAM OR HARDWARE DESIGN AS PERMITTED ABOVE, BE LIABLE TO YOU FOR DAMAGES, 
INCLUDING ANY GENERAL,  SPECIAL, INCIDENTAL OR CONSEQUENTIAL DAMAGES ARISING 
OUT OF THE USE OR INABILITY TO USE THE PROGRAM OR HARDWARE DESIGN (INCLUDING 
BUT NOT LIMITED TO LOSS OF DATA OR DATA BEING RENDERED INACCURATE OR LOSSES 
SUSTAINED BY YOU OR THIRD PARTIES OR A FAILURE OF THE PROGRAM OR HARDWARE 
DESIGN TO OPERATE WITH ANY OTHER PROGRAMS OR HARDWARE), EVEN IF SUCH HOLDER 
OR OTHER PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.

The software included toggles low level hardware signals using undocumented 
Newton ROM functions. It is intended for developer use. You should know what 
you're doing, as this could do damage to your hardware.