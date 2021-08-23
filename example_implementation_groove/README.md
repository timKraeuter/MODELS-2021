Prerequisites:
- Installed java (check with ```java -version```). Tested with version 1.8.0_301.

Run the example using by executing the following command in the bin directory:
```
java -jar Simulator.jar
```
Then load the example by clicking ```File < Open``` and selecting "symposium_example_typed.gps" (Example of the models symposium paper).

Constraints (The atomic propositions are created in groove using graph conditions):

Constraint 1 - LTL property:

G(F(end))


Constraint 2 - LTL property:

!G(r1_accessed_twice_by_1P_2P_r1 | r1_accessed_twice_by_1P_2P_work | r1_accessed_twice_by_2x1P)

Constraint 3 analog to constraint2.

Further resources:
Groove [basic tutorial](https://www.youtube.com/watch?v=R2beaSQ9-NM&t=626s).
