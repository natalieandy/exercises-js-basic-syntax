# My Pseudocode: Is in list

```text

locate procedure TARGET_NUMBER_IN_LIST:
  input: a pile of numbers, call it PILE

  flip every card in the PILE to identify its NUMBER and do the following:
    if NUMBER = 323, then report YES
    if NUMBER != 323, then report NO
end procedure

PILE includes: [5, 6, 7, -80, 900, 323, 150]
signal procedure TARGET_NUMBER_IN_LIST with input: PILE
