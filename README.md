# Storage-Least-Cost-Refill-Optimizer
Determine the most economical and futures-aware storage refill strategy while respecting inventory and operational constraints. While the storage constraints limit the volume put into inventory, we're solving for how much refill volume to buy and in what months, given the current market view.

## Technologies
Excel\
Solver\
Optimization techniques

## Constraints
Storage limits\
Daily injection limits\
Seasonal requirements\
Market price assumptions

## Skills Demonstrated
Optimization\
Economic analysis\
Decision support modeling


<img width="572" height="313" alt="image" src="https://github.com/user-attachments/assets/51c76047-b43c-4fc7-ab06-878c27b54b36" />\



# Example 1 : Static Maximum Daily Injection Quantity
Some fields have a static MDIQ that does not change based on inventory level or month. These are the most straightforward to solve.\
 \
Here, you'll be looking to utilize your full MDIQ in the cheapest months and work you way though the pricing stack until your ending inventory is satisfied. 

<img width="553" height="460" alt="image" src="https://github.com/user-attachments/assets/8517ab59-7c2b-46f1-afd2-2f2c4ae16984" />

Field A LP Formulation:\
<img width="519" height="583" alt="image" src="https://github.com/user-attachments/assets/445bca32-3bde-4216-9201-f2bfd4bd12cd" />


