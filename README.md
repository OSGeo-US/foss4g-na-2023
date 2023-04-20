# FOSS4G NA 2023 Website

```mermaid
classDiagram
    Home -- About
    Home -- Registration
    Home -- Accomodations
    Home -- Program
    Home -- Sponsorship
    Home : - Welcome
    Home : - Description
    Home : - RFP


    Accomodations : - Hotel
    Accomodations : - Room
    Accomodations *-- Transportation

    Transportation : - Type
    Transportation : - Description

    About : - Schedule Overview
    About : - Team
    About : - COC

    Program *-- Session
    Program : - Detailed Schedule

    Session : - Title
    Session : - Description
    Session : - Tags
    Session o-- Presenter

    Presenter : - Name
    Presenter : - Title

    Registration : - Cost
```
