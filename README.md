# Cubepro
Cube pro trio rebuild
defaul settings
Send: M503
Recv: echo:  G21    ; Units in mm (mm)
Recv: 
Recv: echo:Filament settings: Disabled
Recv: echo:  M200 D1.75
Recv: echo:  M200 T1 D1.75
Recv: echo:  M200 D0
Recv: echo:Steps per unit:
Recv: echo: M92 X88.65 Y87.97 Z1100.00
Recv: echo: M92 T0 E690.00
Recv: echo: M92 T1 E415.00
Recv: echo:Maximum feedrates (units/s):
Recv: echo:  M203 X300.00 Y300.00 Z300.00
Recv: echo:  M203 T0 E120.00
Recv:   M203 T1 E100.00
Recv: echo:Maximum Acceleration (units/s2):
Recv: echo:  M201 X1500.00 Y1500.00 Z1500.00
Recv: echo:  M201 T0 E10000.00
Recv:   M201 T1 E120.00
Recv: echo:Acceleration (units/s2): P<print_accel> R<retract_accel> T<travel_accel>
Recv: echo:  M204 P1500.00 R2000.00 T1500.00
Recv: echo:Advanced: B<min_segment_time_us> S<min_feedrate> T<min_travel_feedrate> X<max_x_jerk> Y<max_y_jerk> Z<max_z_jerk> E<max_e_jerk>
Recv: echo:  M205 B20000.00 S0.00 T0.00 X10.00 Y10.00 Z0.30 E0.60
Recv: echo:Home offset:
Recv: echo:  M206 X0.00 Y0.00 Z0.00
Recv: echo:Hotend offsets:
Recv: echo:  M218 T1 X29.90 Y0.00 Z0.000
Recv: echo:Mesh Bed Leveling:
Recv: echo:  M420 S0 Z0.00
Recv: echo:PID settings:
Recv: echo:  M301 P22.20 I1.08 D114.00
Recv: echo:  M301 P22.20 I1.08 D114.00
Recv: echo:Retract: S<length> F<units/m> Z<lift>
Recv: echo:  M207 S1.50 W13.00 F7200.00 Z0.20
Recv: echo:Recover: S<length> F<units/m>
Recv: echo:  M208 S0.00 W0.00 F480.00
Recv: echo:Auto-Retract: S=0 to disable, 1 to interpret E-only moves as retract/recover
Recv: echo:  M209 S0
Recv: echo:Stepper driver current:
Recv: echo:  M906 X1400 Y1400 Z1000
Recv: echo:  M906 T0 E850
Recv: echo:  M906 T1 E500
Recv: 
Recv: echo:Tool-changing:
Recv: echo:  M217 S2.00 E2.00 P3600.00 R3600.00 Z0.00
Recv: ok

Stepper settings
Send: M122
Recv: 		X	Y	Z	E	E1
Recv: Enabled		false	false	false	false	false
Recv: Set current	1400	1400	1000	850	500
Recv: RMS current	1141	1141	820	698	394
Recv: MAX current	1609	1609	1156	984	556
Recv: Run current	19/31	19/31	26/31	22/31	12/31
Recv: Hold current
Recv: CS actual
Recv: PWM scale
Recv: vsense		0=.310	0=.310	1=.165	1=.165	1=.165
Recv: stealthChop
Recv: msteps		16	16	16	16	16
Recv: tstep
Recv: pwm
Recv: threshold
Recv: [mm/s]
Recv: OT prewarn
Recv: OT prewarn has
Recv: been triggered
Recv: off time	0	0	0	0	0
Recv: blank time	24	24	24	24	24
Recv: hysteresis
Recv: -end		-1	-1	-1	-1	-1
Recv: -start		1	1	1	1	1
Recv: Stallguard thrs	0	0	0	0	0
Recv: DRVSTATUS	X	Y	Z	E	E1
Recv: stst		*	*	*	*	*
Recv: olb
Recv: ola						*
Recv: s2gb
Recv: s2ga
Recv: otpw
Recv: ot
Recv: Driver registers:
Recv: 		X	0x00:00:00:80
Recv: 		Y	0x00:00:00:80
Recv: 		Z	0x00:00:00:80
Recv: 		E	0x00:00:00:80
Recv: 		E1	0x00:00:00:A0
Recv: 
Recv: 
Recv: Testing X connection... OK
Recv: Testing Y connection... OK
Recv: Testing Z connection... OK
Recv: Testing E connection... OK
Recv: Testing E1 connection... OK
Recv: ok

Send: M115
Recv: FIRMWARE_NAME:Marlin bugfix-2.0.x (GitHub) SOURCE_CODE_URL:https://github.com/MarlinFirmware/Marlin PROTOCOL_VERSION:1.0 MACHINE_TYPE:Cube Pro Dual Liquid EXTRUDER_COUNT:2 UUID:cede2a2f-41a2-4748-9b12-c55c62f367ff
Recv: Cap:SERIAL_XON_XOFF:0
Recv: Cap:BINARY_FILE_TRANSFER:0
Recv: Cap:EEPROM:1
Recv: Cap:VOLUMETRIC:1
Recv: Cap:AUTOREPORT_TEMP:1
Recv: Cap:PROGRESS:0
Recv: Cap:PRINT_JOB:1
Recv: Cap:AUTOLEVEL:0
Recv: Cap:Z_PROBE:0
Recv: Cap:LEVELING_DATA:1
Recv: Cap:BUILD_PERCENT:0
Recv: Cap:SOFTWARE_POWER:0
Recv: Cap:TOGGLE_LIGHTS:0
Recv: Cap:CASE_LIGHT_BRIGHTNESS:0
Recv: Cap:EMERGENCY_PARSER:0
Recv: Cap:PROMPT_SUPPORT:0
Recv: Cap:AUTOREPORT_SD_STATUS:0
Recv: Cap:THERMAL_PROTECTION:1
Recv: Cap:MOTION_MODES:0
Recv: Cap:CHAMBER_TEMPERATURE:0
Recv: ok
Send: M155 S2
Recv: ok
Send: M504
Recv: echo:EEPROM OK
Recv: ok
Send: M501
Recv: echo:V70 stored settings retrieved (688 bytes; crc 18032)
Recv: echo:  G21    ; Units in mm (mm)
Recv: 
Recv: echo:Filament settings: Disabled
Recv: echo:  M200 D1.75
Recv: echo:  M200 T1 D1.75
Recv: echo:  M200 D0
Recv: echo:Steps per unit:
Recv: echo: M92 X88.65 Y87.97 Z1100.00
Recv: echo: M92 T0 E690.00
Recv: echo: M92 T1 E415.00
Recv: echo:Maximum feedrates (units/s):
Recv: echo:  M203 X300.00 Y300.00 Z300.00
Recv: echo:  M203 T0 E120.00
Recv:   M203 T1 E100.00
Recv: echo:Maximum Acceleration (units/s2):
Recv: echo:  M201 X1500.00 Y1500.00 Z1500.00
Recv: echo:  M201 T0 E10000.00
Recv:   M201 T1 E120.00
Recv: echo:Acceleration (units/s2): P<print_accel> R<retract_accel> T<travel_accel>
Recv: echo:  M204 P1500.00 R2000.00 T1500.00
Recv: echo:Advanced: B<min_segment_time_us> S<min_feedrate> T<min_travel_feedrate> X<max_x_jerk> Y<max_y_jerk> Z<max_z_jerk> E<max_e_jerk>
Recv: echo:  M205 B20000.00 S0.00 T0.00 X10.00 Y10.00 Z0.30 E0.60
Recv: echo:Home offset:
Recv: echo:  M206 X0.00 Y0.00 Z0.00
Recv: echo:Hotend offsets:
Recv: echo:  M218 T1 X29.90 Y0.00 Z0.000
Recv: echo:Mesh Bed Leveling:
Recv: echo:  M420 S0 Z0.00
Recv: echo:PID settings:
Recv: echo:  M301 P22.20 I1.08 D114.00
Recv: echo:  M301 P22.20 I1.08 D114.00
Recv: echo:Retract: S<length> F<units/m> Z<lift>
Recv: echo:  M207 S1.50 W13.00 F7200.00 Z0.20
Recv: echo:Recover: S<length> F<units/m>
Recv: echo:  M208 S0.00 W0.00 F480.00
Recv: echo:Auto-Retract: S=0 to disable, 1 to interpret E-only moves as retract/recover
Recv: echo:  M209 S0
Recv: echo:Stepper driver current:
Recv: echo:  M906 X1400 Y1400 Z1000
Recv: echo:  M906 T0 E850
Recv: echo:  M906 T1 E500
Recv: 
Recv: echo:Tool-changing:
Recv: echo:  M217 S2.00 E2.00 P3600.00 R3600.00 Z0.00
Recv: ok
