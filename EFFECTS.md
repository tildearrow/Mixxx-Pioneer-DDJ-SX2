# Pioneer DDJ-SX2 MIDI Mapping for Mixxx

## Effects Mapping

since Mixxx has a different effect framework, and therefore is not compatible with serato's one, i've tried to map the effect framework to the effect panel somehow.

here's info on it:

- beats selector: effect select
- beats selector push: change effect. the 4 LEDs under the buttons will tell you what are you controlling, which maps to the following:
  - led 1 on: effect 1
  - led 2 on: effect 2
  - led 3 on: effect 3
  - led 4 on: effect chain
- effect knobs: control the effect's parameters.
  - for effects that have more than 3 parameters, use shift+beats selector push.
    the leds will tell you what set of parameters are you controlling.
    - led 1 on: parameters 1 to 3
    - led 2 on: parameters 4 to 6
    - led 3 on: parameters 7 to 9
    - led 4 on: parameters 10 to 12
  - if you ever find any effect with more than 12 parameters, please tell me, and i'll try to do something.
  - and if you're controlling the effect chain, the behavior of the knobs maps to:
    - knob 1: nothing.
    - knob 2: super knob.
    - knob 3: mix knob.
- buttons under effect knobs: controls a parameter's behavior against the super knob. the leds will tell you how is the effect behaving for 2 seconds.
  - no leds on: nothing.
  - all leds on: super knob controls this parameter directly.
  - led 1 on: super knob controls this parameter until it hits the middle.
  - led 4 on: super knob controls this parameter starting from the middle.
  - leds 1 and 4 on: combines behaviors of the previous 2 ones.

that's it for now. sorry, no eject effect/effect chain or turn on/off effect yet. will be added on a later version.