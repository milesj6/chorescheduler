# chorescheduler

This program assigns random chores to team members.

The chore database is an object:

```json
{
    "chore1": {
        "effort": 2,
        "period": 14
    },
    "chore2": {
        "effort": 1,
        "period": 14
    },
    ...
}
```
The team is similarly defined by an object describing each member's name and capacity, where capacity is the estimated effort available in a 14 day period:

```json
{
    "person1": {"capacity": 28},
    "person2": {"capacity": 15},
    ...
}
```

Blah
