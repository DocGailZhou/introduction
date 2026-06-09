# Title: Automatic Design of Autotuners for PID Controllers (Using AI/ML)

## Dr. Gail Zhou PhD Dissertation Abstract 

This dissertation describes three new methods to automatically design autotuners for control systems: the decision tree (TD) method, the simulated annealing and decision tree (SA-DT) method, and simulated annealing and fuzzy logic (SA-FL) method. 

**The Decision Tree method** uses representatives from a class of systems to construct a decision tree autotuner. The autotuner constructed is therefore to be applied to the systems with that trained class, particularly lower order systems. 

**The Simulated Annealing – Decision Tree method** uses a nominal process model but allows the parameters of the model to change within a certain range. A simulated annealing optimization method is used to guide the modifications of controller parameters for extracted example systems, and an inductive inference method is used to construct a decision tree autotuner. This method is intended to be applied to more complex systems or higher order systems. 

**The Simulated Annealing – Fuzzy Logic method** uses a simulated annealing optimization to construct a fuzzy logic auto-tuning (FLA) rule base. The approach produces a FLA rule base automatically by making tests to the process without a priori information about the process or human expertise about the tuning procedures. 

The main advantages of the three methods are 

(1)  the autotuner is constructed automatically using machine learning and / or simulated annealing optimization

(2)  the design procedure is easily repeated or modified to construct autotuners for different types of systems with particular performance requirements

(3)  methods such as Ziegler-Nichols’ and of minimizing integral of time-weighted absolute error (ITAE) and integral of squared error (ISE) are not used to tune the controller or set an initial controller

(4)  neither human experience about the process nor particular specifications on the system dynamics is required to design an autotuner

(5)  controller structures are not limited

(6)  the tuning process is adaptive to the process changes

(7)  practitioners (users) can specify their own controller objectives and ways to modify the controller 

Full PhD Dissertation (AI/ML Application in Process Control): [Automatic design of autotuners for PID controllers](https://voljournals.utk.edu/cgi/viewcontent.cgi?article=12304&context=utk_graddiss). 

 