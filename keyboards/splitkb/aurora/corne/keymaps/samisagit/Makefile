dist: keymap.c
	qmk compile -kb splitkb/aurora/corne/rev1 -km samisagit -e CONVERT_TO=liatris -e BUILD_DIR=keyboards/splitkb/aurora/corne/keymaps/samisagit/dist
README.md: keymap.c
	qmk info -kb splitkb/aurora/corne/rev1 -km samisagit 
keymap.json: keymap.c
	qmk c2json -kb splitkb/aurora/corne/rev1 -km samisagit keymap.c > keymap.json
