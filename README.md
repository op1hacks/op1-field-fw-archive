# OP-1 Field Firmware Archive

An archive of (almost) all OP-1 Field firmware versions with additional info about each file.


## Versions

Versions are listed in chronological order.

### [op1_field_firmware_1_1_2.tfw](firmware/op1_field_firmware_1_1_2.tfw?raw=true)

Release date: 2022-05-12

**Change Log**

* mtp/disk improvements & fixes
* improved ble connection stability
* low battery warning popup
* delayed power switch setting
* enable compressor and limiter on fm transmitter
* interpolate master compressor settings
* add battery info to system settings
* synth: show user samples on shift+T1
* scroll through preset names too long to fit
* transmit OP–1 fm radio station name
* autoset system clock from fm radio


### [op1_field_firmware_1_1_4.tfw](firmware/op1_field_firmware_1_1_4.tfw?raw=true)

Release date: 2022-06-01

**Change Log**

* filter accidental encoder clicks
* 30% lower keyboard latency
* new max brightness color boost (turn to 125%)
* low battery warning tweaks
* new disk mini seek
* fix: reverse loop with start at tape start
* crash fixes
* gfx tweaks


### [op1_field_firmware_1_1_6.tfw](firmware/op1_field_firmware_1_1_6.tfw?raw=true)

Release date: 2022-06-16

**Change Log**

* fix bug where input signal could get distorted
* fix crash when renaming patches with mtp
* fix crash when pitching down synth samples very low
* convert lfo amount on older synth patches to correspond to engine changes
* fix occasional hanging midi notes when switching octave


### [op1_field_firmware_1_2_5.tfw](firmware/op1_field_firmware_1_2_5.tfw?raw=true)

Release date: 2022-08-31

**Change Log**

* per-tape mixer settings
* unlimited lift / drop length
* increased endless sequencer steps to 999
* velocity support in endless, pattern, arpeggio and hold sequencer
* allow deleting snapshot patches
* lift tape head with blue encoder in tape screen
* add lift and drop to master tricks
* tap T1-T4 quickly to switch tracks without soloing
* lifting multiple tracks from tape to sampler keeps mute & pan info
* lift / drop clipboard survives power-off
* don't normalize when dropping audio into synth / drum sampler
* pitch bend did not go back to neutral position
* fix MIDI clock glitch when pressing play
* audio headphone output would not start with some devices
* fix deleting active tape in tape browser
* tweak drum midi velocity response
* mtp improvements and fixes
* other bug & crash fixes
* ui improvements


### [op1_field_firmware_1_2_7.tfw](firmware/op1_field_firmware_1_2_7.tfw?raw=true)

Release date: 2022-09-02

**Change Log**

* fix bug that could cause key presses not to register
* fix crash when switching between certain patches
* fix crash when deleting the last drum snapshot
* fix patch not saved after drum key lift/drop
* multi-track tape drop could insert old audio without clips
* support full external midi range in arpeggio sequencer
* improved midi sync


### [op1_field_firmware_1_2_9.tfw](firmware/op1_field_firmware_1_2_9.tfw?raw=true)

Release date: 2022-09-09

**Change Log**

* fix random factory reset bug when shutting down with usb device connected
* fix noise when dropping multitrack tape to samplers
* fix arpeggio crash


### [op1_field_firmware_1_3_2.tfw](firmware/op1_field_firmware_1_3_2.tfw?raw=true)

Release date: 2022-11-17

**Change Log**

* keyboard velocity sensitivity
* mono / stereo setting for line in
* pre tape pan
* import wav files via mtp
* pre scan for best fm transmit frequencies
* adjust tape speed to external clock
* sync transmit frequency with OB–4
* finger sequencer velocity support
* fixed arpeggio bug with "each" setting
* fixed lift/drop crashes
* misc crash fixes
* misc ui fixes


### [op1_field_firmware_1_3_7.tfw](firmware/op1_field_firmware_1_3_7.tfw?raw=true)

Release date: 2022-12-19

**Change Log**

* fix patch switch crash
* fix shift+T1 crash
* fix tape switch crash
* fix lost sampler recordings
* fix patch drop
* fix minor ui bugs
* keep track level when pressing drum/synth while tape is running


### [op1_field_firmware_1_4_2.tfw](firmware/op1_field_firmware_1_4_2.tfw?raw=true)

Release date: 2023-01-12

**Change Log**

* new vocoder synth engine
* start armed tape recording on external MIDI
* mtp: allow aiff and aifc files for patches* fix patch switch crash


## Missing files

There might be earlier firmware versions that aren't listed here but they're probably not publicly available anyway.


## Sources

* https://teenage.engineering
