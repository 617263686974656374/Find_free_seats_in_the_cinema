# Find_free_seats_in_the_cinema
This Java application simulates the occupancy of seats in a cinema hall. The program randomly assigns each seat as occupied or unoccupied and displays the arrangement as well as statistical information about the occupancy. The simulation models a cinema with 10 rows of 20 seats each, using a 30% probability that any given seat is occupied.

## Features
- **Random Seat Assignment**: Each of the 200 seats has a 30% chance of being marked as occupied.
- **Visual Representation**: Outputs a visual map of the cinema seating, where each row is labeled and seats are marked as occupied (`X`) or free (`.`).
- **Occupancy Statistics**: Calculates and displays the percentage of occupied and free seats for each row and for the entire cinema.

## Output Explanation
- Each line of output represents a row in the cinema from 'A' to 'J'.
- Each row shows 20 seats, marked as either `X` (occupied) or `.` (free).
- At the end of each row, the percentage of free seats along with the total number of free seats in that row is displayed.
- Final output lines show the overall occupancy percentage and the total number of free seats in the cinema.

## Example Output
```
A row    . . . X . X . . . . X . . X . X X . . . 75% = 15 free places
B row    . . X . . X . X . X . . . . . X . . . . 70% = 14 free places
...
J row    X . X . X X . . X . . X . . . . X X . . 55% = 11 free places

The occupancy of the cinema is: 32.5%
Free seats: 130
```
