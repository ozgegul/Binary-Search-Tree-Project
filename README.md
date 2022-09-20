
Patika.dev - Data Structures and Algorithms - Binary Search Tree Project

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] -> Binary Search Tree

1. Write the Binary-Search-Tree steps:

- First value "7" is root.

- Next value "5" is smaller than 7, so it needs to be located on the left of "7".

                   
                          7 (root)
                         / 
                        5
                        
                        
- Next value "1" is smaller than 7 and 5, so it needs to be located on the left of "5".


                          7
                         / 
                        5
                       / 
                      1 


- Next value "8" is grater than 7, so it needs to be located on the right of "7".


                          7
                         / \
                        5   8
                       /
                      1 


- Next value "3" is smaller than 7 and 5, but it is grater than 1, so it needs to be located on the right of "1".


                          7
                         / \
                        5   8
                       /
                      1
                       \
                        3


- Next value "6" is smaller than 7, but grater than 5, so it needs to be located on the right of "5".
                          
                          
                          7
                         / \
                        5   8
                       / \
                      1   6
                       \
                        3


- Next value "0" is smaller than 7, 5 and 1, so it needs to be located on the left of "1".


                          7
                         / \
                        5   8
                       / \
                      1   6
                     / \
                    0   3
                    
                    
- Next value "9" is grater than 7 and 8, so it needs to be located on the right of "8".


                          7
                         / \
                        5   8
                       / \   \
                      1   6   9
                     / \
                    0   3
                    
                    
 - Next value "4" is smaller than 7 and 5, but grater than 1 and 3, so it needs to be located on the right of "3".
  
  
                          7
                         / \
                        5   8
                       / \   \
                      1   6   9
                     / \
                    0   3
                         \
                          4
                          
                          
  - Next value "2" is smaller than 7 and 5, grater than 1 but smaller than 3, so it needs to be located on the left of "3".
  
  
                          7
                         / \
                        5   8
                       / \   \
                      1   6   9
                     / \
                    0   3
                       / \
                      2   4
                 

