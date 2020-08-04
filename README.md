# City Cycles

## From User Stories to a Domain Model

```
As a person,
So that I can use a bike,
I'd like a docking station to release a bike.
```
```
As a person,
So that I can use a good bike,
I'd like to see if a bike is working
```

||Nouns|Verbs|
|---|---|---|
|user story 1|person|use (bike)|
||bike||
||docking station|release (bike)|
||||
|user story 2|person|use (good bike)|
||good bike||
||bike|working?|

|objects|messages|
|---|---|
|Person||
|Bike|working?|
|DockingStation|release_bike|

```
Bike <-- working? --> true/false
DockingStation <-- release_bike --> a Bike
```
