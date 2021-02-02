In this folder, there are several benchmarks for the main variants of the Role Mining Problem.
The Number of Users and Permissions, the Ocuppancy Rate, an Upper Bound on the minimum number of Roles (RB) as well as the best known solutions (BEST) are given in the Tables below.

They benchmarks grouped into three different categories depending on ther size. 

Small           |  #Users  |  #PRMS  |  Occupany  |  RB*  |  BEST  |    
Small_1.rmp     |      50  |     50  |    24,00%  |  25   |    24  |
Small_2.rmp     |      50  |    100  |    43,28%  |  25   |    29  |
Small_3.rmp     |     100  |    100  |    27,38%  |  25   |    31  |
Small_4.rmp     |     100  |    100  |    38,68%  |  25   |    34  |
Small_5.rmp     |     100  |    200  |            |       |        |
Small_6.rmp     |     100  |    200  |            |       |        |

Medium          |  #Users  |  #PRMS  |  Occupany  |  RB*  |  BEST  |    
Medium_1.rmp    |     500  |    500  |            |       |        |
Medium_2.rmp    |     500  |    500  |            |       |        |
Medium_3.rmp    |     500  |   1000  |            |       |        |
Medium_4.rmp    |     500  |   1000  |            |       |        |

Large           |  #Users  |  #PRMS  |  Occupany  |  RB*  |  BEST  |    
Large_1.rmp     |    1000  |   1000  |            |       |        |
Large_2.rmp     |    1000  |   1000  |            |       |        |
Large_3.rmp     |    1000  |   5000  |            |       |        |
Large_4.rmp     |    1000  |   5000  |            |       |        |

* RB: The Role Bound evolves from the number of roles used for the creation of the Benchmark, which means, that there is a theoretical solution with exactly RUB roles. 
       Thus, this can be used as reference point for the resultig number of roles. In some cases the minimum number of roles can be below this threshold.
       
Furthermore, there are Benchmarks reflecting the department structures found in enterprises. 
At this, each permission is assigned to one category, while users can beassigned to more than one category. 
