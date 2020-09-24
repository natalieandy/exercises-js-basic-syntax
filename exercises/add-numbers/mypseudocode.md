# My Pseudocode: Add Numbers

```text

locate procedure ADD_NUMBERS:
  input: a pile of NUMBERS, call it PILE

  flip the first card and write down its NUMBER on a sticky note, call it TOTAL_NOW

  for every NUMBER in the PILE, do the following:
    NUMBER + TOTAL_NOW

  report final TOTAL_NOW
end procedure

PILE includes: [5, 10, 15, 20, 25]
signal procedure ADD_NUMBERS with PILE input
