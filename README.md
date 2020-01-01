# Random-Green-3Pages
Hey Girls :) I created a new repository for you to see the other option for randomization with 3 pages. I didn't want to change everything in our project because we still have to decide which version we want to use and changing everything and then changing it back would leave to much room for mistakes. :P 

Just for your info and for better understanding what I did: 

- We have two possibe ways for randomization 
  
  1. Using an ID and then creating 3 different equally sized groups.
     Every third page would be the same. 
     
  2. Using random.math() instead. 
     This function creates a random number between 0  and 1, afterwards I distributed the participants like        this: 
          0-0.33 -->  No treatment
          0.33-0.66 --> Treatment 1 
          0.66 - 1 --> Treatment 2 

I think the second version would also work if we have it somewhere online. 
With the first one I'm not sure (Anastasiia said it probably wouldn't work in the web ...but I don't know how to make it accessible online and unfortunately couldn't test it to find out if there really is a problem. :S)

I think I would put both versions in our project files (one commented out) that he sees that we put some thought into it and tried different things. :) 


- And then we also have 2 possible ways for redirection.

  1. The first one is directing everyone to the same page but changing what is displayed on the page based on the Treatment    group.  
  --> The randomization would be in the delivery file.
  
  2. The second option would be to create 3 different pages and directing everyone to a different page based on the treatment group. 
  --> The ramdomization takes place while clicking on the button of the chosen product (productChoice-file)
  
These 2 options are basically the same. Creatng 3 pages requires a lot more code, and might not be as "pretty" as the first option. BUT with the second option (3 pages) we could impliment the treatment using html and not just with pictures. 

Since Anastasiia is pretty into HTML (:P) I would go for the second 3 page option, but also leave the other option in the files commented out.

So now we have to decide for 1 option in both cases. :P 

And HAPPY NEW YEAR btw. ;) 
