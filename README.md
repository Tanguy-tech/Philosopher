
👨🏻‍💻 This is the README file for 42 project philosopher

👨🏼‍🎓 Authors: tbillon - prom 2020 contact: tbillon@student.42lyon.fr

📒 Subject: [Find the Philosopher subject HERE](https://cdn.intra.42.fr/pdf/pdf/34975/en.subject.pdf)

![Made with C](https://forthebadge.com/images/badges/made-with-c.svg) ![Powered by coffee](https://forthebadge.com/images/badges/powered-by-coffee.svg) ![Built with love](https://forthebadge.com/images/badges/built-with-love.svg)

- This project is to be coded in C, following the 42's Norm. Any leak, crash, undefinedbehavior, or norm error means 0 to the project.
- Several philosophers are sitting at a round table doing one of three things: eating,thinking, or sleeping.
- While eating, they are not thinking or sleeping, while sleeping, they are not eatingor thinking and of course, while thinking, they are not eating or sleeping.
- The philosophers sit at a circular table with a large bowl of spaghetti in the center.
- There are some forks on the table.
- As spaghetti is difficult to serve and eat with a single fork, it is assumed that aphilosopher must eat with two forks, one for each hand.
- The philosophers must never be starving.
- Every philosopher needs to eat.
- Philosophers don’t speak with each other.
- Philosophers don’t know when another philosopher is about to die.
- Each time a philosopher has finished eating, he will drop his forks and start sleeping.
- When a philosopher is done sleeping, he will start thinking.
- The simulation stops when a philosopher dies.
- Each program should have the same options: 
    - number_of_philosophers time_to_dietime_to_eat time_to_sleep [number_of_times_each_philosopher_must_eat]
    - number_of_philosophers: is the number of philosophers and also the numberof forks
    - time_to_die: is in milliseconds, if a philosopher doesn’t start eating ’time_to_die’milliseconds after starting his last meal or the beginning of the simulation, it dies.
    - time_to_eat: is in milliseconds and is the time it takes for a philosopher toeat. During that time he will need to keep the two forks.
    - time_to_sleep: is in milliseconds and is the time the philosopher will spendsleeping.
    - number_of_times_each_philosopher_must_eat: argument is optional, if allphilosophers eat at least ’number_of_times_each_philosopher_must_eat’ thesimulation will stop. If not specified, the simulation will stop only at the deathof a philosopher.
- Each philosopher should be given a number from 1 to ’number_of_philosophers’.
- Philosopher number 1 is next to philosopher number ’number_of_philosophers’.Any other philosopher with the number N is seated between philosopher N - 1 andphilosopher N + 1
- Any change of status of a philosopher must be written as follows (with X replacedwith the philosopher number and timestamp_in_ms the current timestamp in mil-liseconds)
- timestamp_in_ms X has taken a fork
- timestamp_in_ms X is eating
- timestamp_in_ms X is sleeping
- timestamp_in_ms X is thinking
- timestamp_in_ms X died
- The status printed should not be scrambled or intertwined with another philoso-pher’s status.
- You can’t have more than 10 ms between the death of a philosopher and when itwill print its death.•Again, philosophers should avoid dying!