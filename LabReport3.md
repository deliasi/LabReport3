# Cse 15L LAb Report 3

## Researching Commands - Grep 
For my lab report, I focused on the grep command.
A shortcut I found useful for finding different commmand line options for grep was using the

         man grep
         
command.

img

### First Command Line Option (Grep -A/-B)
This command allows us to display as many lines before or after our input matches.

Using -A:

      DERRICKS-MacBook-Air:media alenooshhambarchian$ grep -A 5 "wait" 5_Legal_Groups.txt
      client waiting room. The building is close in, across the street
      from West High and two blocks from the Gateway. It has its own
      parking, something that's hard to find downtown and which has been
      a problem for staff as well as clients. Owning and sharing the
      building and not paying rent times five will save the non-profit
      agencies about $375,000 each year. My assistant, Charity
      DERRICKS-MacBook-Air:media alenooshhambarchian$ 
    
    
-B:

        DERRICKS-MacBook-Air:media alenooshhambarchian$ grep -B 5 "wait" 5_Legal_Groups.txt
        the Multi-Cultural Legal Center, the Senior Lawyer Volunteer
        Project and Utah Legal Services will share the new facility, and
        last Wednesday their board members were given a tour of the
        Community Legal Center hosted by staff members of the five
        agencies. All of the agencies can share the same reception area and
        client waiting room. The building is close in, across the street
        DERRICKS-MacBook-Air:media alenooshhambarchian$ 

### Second Command Line Option (Grep -c)
This command allows us to find the occurances of patterns in out text files.

         DERRICKS-MacBook-Air:media alenooshhambarchian$ grep -c 'say' Farm_workers.txt
         2
         DERRICKS-MacBook-Air:media alenooshhambarchian$ grep -c 'finally' Farm_workers.txt
         0
         DERRICKS-MacBook-Air:media alenooshhambarchian$ 


### Third Command Line Option (Grep -o)
 
f

        DERRICKS-MacBook-Air:media alenooshhambarchian$ grep -o "say"  Ginny_Kilgore.txt
        say
        say
        DERRICKS-MacBook-Air:media alenooshhambarchian$ grep -o "to" Ginny_Kilgore.txt
        to
        to
        to
        to
        to
        to
        to
        to
        to
        to
        to
        to
        to
        to
        to
        to
        to
        DERRICKS-MacBook-Air:media alenooshhambarchian$ 
        
### Fourth Command Line Option (Grep -o)
        
    
    
 

