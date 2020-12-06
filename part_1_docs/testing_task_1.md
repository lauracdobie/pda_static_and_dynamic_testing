### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:


  def check_for_ace(self, card):
  # Should be card.value == 1
    if card.value = 1:
      return True
  # Missing colon at the end of else
    else
      return False
  
  # Should be def, not dif
  dif highest_card(self, card1 card2):
  # There needs to be a comma between card1 and card2. Indentiation error.
  if card1.value > card2.value:
    return card
  # This should be card1
  else:
    return card2
  

# Indentation error
def cards_total(self, cards):
  total
# Total needs to be set to 0 to start with, or its value will not increment as we iterate over the list
  for card in cards:
    total += card.value
# Need to convert total to string and add in a space after the f in of. Indentation error for return."
    return "You have a total of" + total
  
```
