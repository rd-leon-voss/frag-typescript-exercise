## REWE Timeslots Exercise

### Start

Enter `npm start` to run execute the script `index.ts`.

## Tasks

### 1) Processing slots

a) Create a **model** for a slot and parse slotsData into an array of this model

### 2) Slot summary

a) Generate **report** for all zip codes. The report should contain the following information:

- Zip code
- number of slots for this zip code
- total capacity of all slots for this zip code
- average cost of all slots for this zip code (in €)
- average duration of all slots for this zip code (in minutes)

b) Display the report in the console. Use [console.table()](https://developer.mozilla.org/en-US/docs/Web/API/console/table) to format the output
| Zip code | # of slots | Total capacity | Average cost [€] | Average duration |
|----------|------------|----------------|------------------|------------------|
| 80335 | 1 | 5 | 3.90€ | 120 |

### 3) Bonus

a) Sort the report by the number of slots for this zip code

b) Display the average duration as `hh:mm`
