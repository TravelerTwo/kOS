## Script Layout

PARAMETERS.

TO-DO LIST.

INITIALIZATION (Clearscreen, Steeringmanager, Terminal, etc.).

FUNCTIONS.

VARIABLES.
- Physical properties.
-  Scalars.
- Vectors.
- Geopositions.
- Dependent variables.
- System.

PRINT TERMINAL UI.

STEERING CONTROL (rcs, sas, steeringCtrl, throttleCtrl, etc.).

MAIN LOOP.

RELEASE STEERING.

## Script Syntax(?)

Instructions/Keywords = All uppercase except when followed by ()
at()          IN      min()     RUN     WAIT
BREAK         IS      OFF       SET
CLEARSCREEN   list()  ON        STAGE
ELSE          LIST    PARAMETER TO
FOR           LOCAL   PRESERVE  TOGGLE
FUNCTION      LOCK    PRINT     UNLOCK
IF            max()   REMOVE    UNTIL

Function name         = Lowercase or lowercase_lowercase  :FUNCTION vxcl_up {
Logic operators       = All uppercase                     :NOT, AND, OR, TRUE, FALSE
Physical properties   = Single letter                     :LOCAL g IS body:mu / body:position:sqrmagnitude)
