# Pseudocode: Find Largest Number

<!--> I know that adding the quotes might seem misleading bc single quotes are v important in JS but it personally signals to me that I'm naming something<!-->
```text
spellout procedure "FindHighestNumber" :
  input: a pile of numbers, call it "PILE"

  flip card to identify the NUMBER, record it and refer to it as "highest_number_now"

  for every NUMBER in the PILE:
    if NUMBER > highest_number_now, then:
    replace highest_number_now with the NUMBER on the "scratch card"
    end process after examining all numbers

  print final highest_number_now

end procedure

input includes: [8, 41, 36, 7, 900]
signal procedure "FindHighestNumber" with input PILE
