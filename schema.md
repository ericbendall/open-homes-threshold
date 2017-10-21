# Schema

## Guest Family
id | name | hostingId

## Host Family
id | name | <address> | profileId | hostingId

**Not sure if this should be it's own separate table, or should be moved into guest**
## Hosting
id | hostId | guestId | status | nextPhaseDate

## Host Profile
id | name | isNew | primingCost | vettingCost | placementCost | mentoringCost | debriefCost | permPlacementCost | hostsUntilGraduation | graduateProfileId

## Tasks
id | name | description | cost per week | startDate | duration

## Vacations
id | name | hostId | startDate | endDate
