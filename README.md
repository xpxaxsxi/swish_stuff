# swish_stuff
Swish links etc.

https://swish.swi-prolog.org/p/ADFS2.pl

My idea of how to visualize a  directed  graph and use the visual directly in prolog code. 


```
1 >>  2. 2 >>  3. 3 >>  4. 4 >>  5.
         2          >>           5.
1            <<                  5.
         2  << 3. 3       <<     5.
         2        <<             5.      
                 
k >> m. m >> n.
k    <<      n.

                 
a >> b. b >> c. c >> d.
a         <<         d. 
```
