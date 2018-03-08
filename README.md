# comcores
C code related to the computation of communitiy cores


## Info:

Feel free to use these lines as you wish. 

## To compile:

- gcc comcores1.c -O3 -o comcores1

## To execute:

"./comcore1 k com.txt pairs.txt"
- com.txt contains the list of all communities.  
One community on each line:  
i0 i1 i2 ... in  
where:  
i0 i1 i2 ... in is the list of the nodes in the community.
- pair.txt contains the list of all pairs of nodes appearing together more that k times in a same community: "node1 node2 times" on each line.


## Performance:

TODO

## Initial contributors

Maximilien Danisch and Jean-Loup Guillaume  
Mars 2018  
http://bit.ly/danisch  
maximilien.danisch@gmail.com

