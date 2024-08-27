# remind
A repo for code associated with analyzing Apple Reminders data

# requirements
## Data Sources
As a couple, we make use of a set of shared reminder lists named the following:
- to-do's
- wedding
- Week-of Wedding
- inbox
- chores
- wellness
All of these reminder lists will be included in this ETL

## Event Streaming
The ETL needs to be able to read real-time updates and additions to the reminders lists itemized above.

## Analytics
a set of dashboards will be created that make use of the reminder data. They too will update in real-time. These are the following things that I would like to know at a glance:
- How is our event completion? measured as the percent of reminders completed on time. overall, by list, how is it trending?
