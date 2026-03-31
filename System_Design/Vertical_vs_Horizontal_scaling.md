## **Vertical vs horizontal scaling**

![alt](../system-design-images/image.png)


#### Vertical scaling:
1. Simple but has ceiling, and more expensive.
2. Single point of failure.
3. Inter process communication.
4. Consistent 
5. Hardware limit

-------------------------------------------------------

#### Hardware scaling:
1. Ulimate bit need coordination
2. Spreading the loads across them.
3. Load Balancing required.
4. Resilient
5. Inter Network call (RPC)
6. Data Inconsistancy
7. Scale well as user increases.