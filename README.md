# comcore
C code related to the computation of communitiy cores


## Info:

Feel free to use these lines as you wish. 

## To compile:

- gcc comcore1.c -O3 -o comcore1

## To execute:

"./comcore1 k com.txt pairs.txt"
- com.txt contains the list of all communities.  
One community on each line:  
i0 i1 i2 ... in  
where:  
i0 i1 i2 ... in is the list of the nodes in the community.
- pair.txt contains the list of all pairs of nodes appearing together more that k times in a same community: "node1 node2 times" on each line.


## Performance:

On a commodity machine (a mid-range laptop with an SSD hard drive):
- using http://snap.stanford.edu/data/com-Youtube.html  
"./comcore1 10 com-youtube.all.cmty.txt Youtube10" is instantaneous.
- using http://snap.stanford.edu/data/com-Friendster.html  
"./comcore1 10 com-friendster.all.cmty.txt friendster10" takes 4 minutes.
- using http://snap.stanford.edu/data/com-LiveJournal.html  
"./comcore1 10 com-lj.all.cmty.txt lj10" takes 4 minutes.

## Initial contributors:

Maximilien Danisch and Jean-Loup Guillaume  
Mars 2018  
http://bit.ly/danisch  
maximilien.danisch@gmail.com

