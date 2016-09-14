# Universal WCO Reporting Tool: Deriving Usage Metrics From WCO CSV Exports

### Metrics included:
    • Major Code
    • Faculty/Staff/Student
    • Equipment (for purchasing, and loaner gear)
    • Day/Time of Checkout (for scheduling)
    • Day/Time of Checkin (for scheduling)

### Optional Metrics Included:
    • Status of reservation (reservations never picked up)
    • Late return (by hour amount)
    • Frequent students (by hour amount)

### How To Use:
    • In Web Check Out:
        • Select Usage Report from under the Reports tab in WCO
![Report](https://github.com/compagnb/WCO-Reporting-Python/blob/master/images/report.png)

        • Choose your Check-out Center
![Center](https://github.com/compagnb/WCO-Reporting-Python/blob/master/images/ckoutcenter.png)

        • Select all states applicable (Checkout, completed.... etc)
![States](https://github.com/compagnb/WCO-Reporting-Python/blob/master/images/state.png)

        • Select start date and time
        • select end date and time
        • ensure the following result collumns are included in your output:
            • "Patron Department"
            • "Effective Patron Class"
            • "Item Names"
            • Summary
            • "Pickup Time"
            • "Actual Return Time"
            • "Effective Return Time"
            • "Return Time"
            • State
            • Patron
        • export results as a CSV
    • Exporting graphs/readable report:
        • Equipment Bar Charts -- coming soon.
        • Day Line Charts (Checkouts/Returns per hour) -- coming soon.
        • Major distribution chart -- coming soon.
