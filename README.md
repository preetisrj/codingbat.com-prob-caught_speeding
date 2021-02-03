# codingbat.com-prob-caught_speeding
def caught_speeding(speed, is_birthday):
  no_ticket=0
  small_ticket=1
  big_ticket=2
  
  while is_birthday:
    if speed<86:
      return big_ticket
    elif speed <65:
      return no_ticket
    elif speed>65 or speed<86:
      return small_ticket
  else:
    if speed<61:
      return no_ticket
    elif  speed>=61 or speed<=80:
      return small_ticket
      
    else:
      
      return big_ticket
    
