# FOSS4G NA 2023 Website

-   test

```mermaid
classDiagram
    Home -- About
    Home -- CallForPresentations
    Home -- Accomodations
    Home -- Program
    Home -- Sponsorship
    Home : - Welcome
    Home : - Sponsors

    About : + Schedule Overview
    About : * Accomodations
    About : - COC

    CallForPresentations : - dd

    Accomodations : - Hotel
    Accomodations : - Room
    Accomodations *-- Transportation

    Transportation : - Type
    Transportation : - Description


    Program *-- Session
    Program : - Detailed Schedule

    Session : - Title
    Session : - Description
    Session : - Tags
    Session o-- Presenter

    Presenter : - Name
    Presenter : - Title


```
