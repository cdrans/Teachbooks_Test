(intro)=
# Introduction
When we construct a Free Body Diagram of an engineering system and analyze the equilibrium state of that body, we are examining only the forces and moments acting on the isolated body. However, for engineering design, we eventually need to examine how loads are carried within a structure so we can evaluate if it will fail or not. Within this chapter, we will examine this process of evaluating internal loads and look at ways of visualizing internal loading distributions. In fact, you have technically already done this for one type of structure — a truss structure. We will build upon the internal force analysis you have already performed for truss structures and look at internal loading from a more general perspective. 

## Concept of a Load Path
What is the purpose or function of a structure? In simple terms, you can define a structure as *a construction designed to carry and transmit loads from one point to another*. When we create a Free Body Diagram of a structure, we define the origin of these loads as applied forces and moments (the action forces of the surroundings on the structure) and the destination of these loads as the support reaction forces and moments. The manner in which these loads are transmitted through the structure is known as the **Load Path**.
The best way to understand the concept of a load path is to examine a few simple structures. First, let’s consider two truss structures of the same overall shape and size, but with different applied loads as illustrated in Figure 1.1 and Figure 1.2. Using the Free Body Diagrams provided in these figures, we can easily calculate the reaction forces for both load cases using equilibrium.
For Load Case 1, we obtain:

$$\begin{align*} 
    &\sum {\mathop {{F_x}}\limits^{ \to  + } :{A_x}}  = 0\\
    &\sum {\mathop {{F_y}}\limits^{ \uparrow  + } :{A_y} + {C_y} - 10~kN}  = 0\\
    &\sum {\mathop {{M_A}}\limits^{ccw + } : - \left( {10~kN} \right)} \left( L \right) + \left( {{C_y}} \right)\left( {2L} \right) = 0
\end{align*}$$
