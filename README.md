# FUNCTION-OUTPUTS
#Functions with outputs
def format_name(f_name, l_name):
  if f_name=="" or l_name=="":
    #if False return wll be skipped to next code
    return "no input given"
  formatted_f_name = f_name.title()
  formatted_l_name = l_name.title()
  #ends teh program nand the result is saved to return 
  return f"Result:{formatted_f_name} {formatted_l_name}"


print(format_name(input("first name?"),input("last name?")))

 

  
