TECHTREE ENTRIES
bbase-assim.odf				1	borpod1.odf	// Borg Assimilation Nexus
borW_bluebeam-nexus.odf		1	borpod1.odf	// Borg Auto-Assimilator - Nexus variant
// borW_bluebeam-nexus2.odf	1	borpod1.odf	// Borg Auto-Assimilator - Nexus variant
borRW_areaboard.odf			1	borpod2.odf // Borg Area Boarding
uball_effect_areaboard.odf	1	borpod2.odf // Borg Area Boarding
borW_areaboardA.odf			1	borpod2.odf // Borg Area Boarding
borRW_arearecrew.odf		0				// Borg Area Recrewing
borW_arearecrewA.odf		0				// Borg Area Recrewing
borW_generate_crew.odf		0
uball_effect_arearecrew.odf	0				// Borg Area Recrewing

HOTKEY ENTRIES
# Assimilation Nexus - A is for "Assimilation"
bc_bbase-assim {
	+ keyboard	A
	- keyboard	Control
	- keyboard	Shift
	- keyboard	Alt
}
wc_borW_bluebeam-nexus {
	+ keyboard	F3
	- keyboard	Control
	- keyboard	Shift
	- keyboard	Alt
}

BUTTON ENTRIES
# build button
@reference=128
@tmaterial=interface
b_bbase-assim			gbrefit1	0	64	64	64	#	1	2
# special weapon
@reference=64
@tmaterial=interface
b_borW_bluebeam-nexus	gbbaabore00	0	0	64	64	

CONSTRUCTOR ENTRIES
Included for your convenience are ODFs for the vanilla Borg constructor,
and a new ODF that includes an entry for the Assimilation Nexus.
However, if you wish to just add the entry yourself,
the line is provided below:

buildItem13 = "bbase-assim.odf"

SPRITE ENTRIES
@tmaterial=alpha
@reference=32
mapicon_empty		mapicons		31	31	1	1