# Time-Off Management Microservice

A full-lifecycle time-off management microservice, built as a technical 
take-home assessment for Wizdaa.

## What it does
- Manages the complete time-off request lifecycle (request → approval → 
  balance update)
- Uses optimistic locking to prevent race conditions on concurrent 
  balance updates
- Includes a mock HCM (Human Capital Management) sync layer to simulate 
  integration with external HR systems
- Backed by a full unit test suite covering core business logic

## Tech stack
NestJS · TypeScript · SQLite

## My role
Solo-built as a recruitment assessment — designed the data model, 
concurrency handling, and test coverage under a tight turnaround.

## Note
This repo showcases the project's structure. Full source is public — 
see the [live repo](https://github.com/Ummesalma53/Time-Off-MicroService).
