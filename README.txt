This repository contains various Pd abstractions I personally use, which might be helpful to others.

[bin2any] converts a binary value entered either as a list of 1s and 0s, or as a symbol, to either a decimal, a hexadecimal, or an octal value. The Pd-extended version is called [bin2any_extended]

[dyn_val] is an abstraction that enables typing numeral values without needing to click on number atoms.

[loop] is a sophisticated vanilla loop abstraction.

[vanillaJoin] is a vanilla list abstraction with all hot inlets, where you don't need to specify if you enter a float or a symbol. It imitates Max's [join]. It's Pd-extended counterpart is called [extendedJoin].

[vanillaPak] is a vanilla [pack] abstraction with all hot inlets. It's Pd-extended counterpart is called [extendedPak].

[vanillaS2f] is a vanilla abstraction to convert symbols with numeral characters to floats.
