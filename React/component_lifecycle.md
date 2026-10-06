A component goes through three stages:

- mount (first appears)

- update (re-renders when state, props or context change)

- unmount (removed).

when unmounting and mounting the states get erased not like re-renders 

what causes unmount and mount:

- Condition true to false : unmount

- Condition false to true : mount

- Key added or removed in a list : mount or unmount

- key prop changes: unmount then mount

- Type at the same position changes : unmount then mount

- Parent unmounts : all children unmount