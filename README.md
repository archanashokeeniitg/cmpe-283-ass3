# cmpe-283-ass3

## Archana Shokeen(015237378)

# Question

For whichever assignment you chose to complete CPUID 0x4FFFFFFD and 0x4FFFFFFC:
3. Comment on the frequency of exits – does the number of exits increase at a stable rate? Or are there 
more exits performed during certain VM operations? Approximately how many exits does a full VM 
boot entail?
4. Of the exit types defined in the SDM, which are the most frequent? Least?

# Steps

Follow the assignment 2 details -

https://github.com/archanashokeeniitg/cmpe283_ass2


# Answers


Comment on the frequency of exits 

No, the number of exits do not increase at a stable rate.

Yes, There are more exits performing during certain VM operations. A full VM boot entail around ~830000 exits.


Most Frequent Exit:


    Exit number 1- External Interrupt

    Exit number 32 - WRMSR

    Exit number 48 - EPT Violation
	
	
Least Frequent Exit :

    Exit number 29 - MOV DR
  
	  Exit number 54 - WBINVD
  
	  Exit number 55 -  XSETBV
	
