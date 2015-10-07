This repository contains various Pd abstractions I personally use, which might be helpful to others.
Most of them are vanilla, but some extended versions are included, whenever it's not possible to use a common abstraction both for vanilla and extended. All abstractions support both Pd versions this way.

[bin2any] converts a binary value entered either as a list of 1s and 0s, or as a symbol, to either a decimal, a hexadecimal, or an octal value. The Pd-extended version is called [bin2any_extended]

[clip_abs] solves the issue [clip] has when the first argument is greater than the second

[loop] is a sophisticated vanilla loop abstraction.

[map] maps a range of values to another range.

[mtof_tune] converts MIDI notes to frequencies which can be tuned according to tuning A.

[no_click_val] vanill abstraction that enables typing numeral values without needing to click on number atoms.

[round_int] vanilla abstraction that rounds a float to the nearest integer.

[vanillaJoin] vanilla list abstraction with all hot inlets, where you don't need to specify if you enter a float or a symbol. It imitates Max's [join]. It's Pd-extended counterpart is called [extendedJoin].

[vanillaPak] vanilla float list abstraction with all hot inlets. It's Pd-extended counterpart is called [extendedPak].

[vanillaS2f] vanilla abstraction that converts symbols with numeral characters to floats.
