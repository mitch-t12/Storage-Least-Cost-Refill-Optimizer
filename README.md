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


<img width="644" height="274" alt="image" src="https://github.com/user-attachments/assets/81faa4ec-6ced-4dda-b850-29767b70066c" />
<br>
<br>
<br>
<br>
<br>
  
# Example 1 : Static Maximum Daily Injection Quantity
Some fields have a static MDIQ that does not change based on inventory level or month. These are the most straightforward to solve.\
 \
Here, you'll be looking to utilize your full MDIQ in the cheapest months and work you way though the pricing stack until your ending inventory is satisfied. 

<img width="738" height="478" alt="image" src="https://github.com/user-attachments/assets/7e2e2ab0-2181-41af-95d8-6726ad934b62" />


## Field A LP Formulation:
<br>
<br>

<img width="595" height="518" alt="image" src="https://github.com/user-attachments/assets/a482a4b3-0da7-4d28-bb76-e65cd247157d" />



