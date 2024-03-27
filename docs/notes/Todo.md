# TODO

## MUST DO's for Putting ON CV
[ ] Updated README
[ ] Create Database Setup SQL File
[ ] Initiate Git Repository

## Improvements to current scope
[ ] Refactor JS - Use seperate HTML Pages?
[ ] Optimise SQL Queries (views are slow) 
    [ ] migrate queries from using 'VDSR' to 'VDLS'
[ ] Rethink design of Index Classes


## Additional features
[ ] Itinerary Finder
[ ] Tool to import missing data from backup directory






# DONE

## Support for Intrepid API
[X] Extract tour name
[X] Extract Departures
[X] Update SQL Queries/View to ignore price changes to or from 0 (no availability). DONE for alert Report

## Set Up 'Tour' Controller
[x] Create Method (tour/create)
[X] Sync Method   (tour/sync)
[X] Delete Method (tour/delete)

## Setup 'Departure' Controller 
[X] Watch Method  (departure/watch)
[X] Unwatch Method (departure/unwatch)

## Setup 'reports' Controller
[X] Tours Method (report/tours)
[X] departures Method (report/departures)
[X] history Method (report/history)

## Migrate UI to new backend
[X] Adjust API pointers
[X] Get Filter by Watchlist working - 2024-03-20: Works but may need cleaning up in future.
 
## Improvements to framework
[X] Support for route rewriting.


## Clean Up Index Classes
[X] Use external SQL files
[X] Inherit from base Index Class

## Report Classes
[X] Refactor to use 'SqlAdapt' utility 


## Make TourDataExtractor Save a backup copy of tour data for archiving/data analysis purposes.
[X] Done

## Extend Sync Functionality to check for changes then create Alerts.
[X] SQL view to show changes to price and availability.
[X] Alerts Report / HTTP API
[X] Render Alerts Data in UI table.

## Implement CRON jobs with automatic tour syncing
[X] Changes to framework to allow cron jobs.
[X] Implemented random tour sync feature

## Clean Up Repository Classes
[X] Inherit from base Repository Class



