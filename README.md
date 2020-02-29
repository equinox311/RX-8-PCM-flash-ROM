# RX-8-PCM-flash-ROM
Flash ROM dumps I have pulled from RX-8 PCMs

ECU ID (I think) 60E0FC00 notable addresses off the hop: 

0x1FF5: SBL_END, end of bootloader section??

0x2000: 60E0FC00 Copr.DENSO2000, application jump address?

0x5D90C: MazdA, this is actually the secret word for the programming access seed/key algorithm

0x6D300: N3Z2EBWW.Z05 60E0FC00 Copr.DENSO2000SSW-N3Z2EU000.HEX, Calibration software start address + cal ID ??
