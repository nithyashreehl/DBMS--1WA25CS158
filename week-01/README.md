Consider the Insurance database given below. The data types are specified.
PERSON (driver_id: String, name: String, address: String)
CAR (reg_num: String, model: String, year: int)
ACCIDENT (report_num: int, accident_date: date, location: String)
OWNS (driver_id: String, reg_num: String)
PARTICIPATED (driver_id: String,reg_num: String, report_num: int, damage_amount: int)
List of operations
1. Create a Database called “INSURANCE DATABASE”
2. Create the above tables by properly specifying the primary keys and the foreign keys.
3. Enter at least five tuples for each relation. 4. Update the damage amount to 25000 for the car with a specific reg_num (example: 'K
A053408') for which the accident report number was 12.
5. Add a new accident to the database.
6. Display Accident date and location
7. Display driver id who did the accident damage greater than or equal to Rs.25000
