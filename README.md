dzit
====

dzit is an implementation attempt to solve the agenda scheduling problem, using a constraint dsl

the project is divided in two modules: 
 * the *core* containing the scheduling algorithms interpreting the DSL constraints.
 * the *binding* representing a implementation specification, displaying or generating calendars

here would be a list of constraints types:

 * living person: capabilities (domain, grade, wishes, ...) 
 * inanimate asset: capabilities (efficiency, operators, number of participants, ...)
 * reglementation instance: limits (hours, days, months, hollidays ...)
 * murphy: unexpected (illness, closed, ...)

The core element is independent of the constraint types, several algorithms are attempting to find a fair and optimal solution.
depending on the biding type, the interface should handle new constraints types and assets, without modifying the core implementation.

the direct application of this project would be sport events planificaton, shift sheduling, schools, work rotations, ...
