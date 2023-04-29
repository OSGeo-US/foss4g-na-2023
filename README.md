# FOSS4G NA 2023 Website

```mermaid
classDiagram
    Home -- About
    Home -- CallForPresentations
    Home -- Program
    Home -- Sponsorship
    Home : - Welcome
    Home : - Sponsors

    About : * CODE OF CONDUCT
    About : * SCHEDULE OVERVIEW
    About : * ACCOMODATIONS
    About : * REGISTRATION

    CallForPresentations : * DESCRIPTION
    CallForPresentations : * WHAT TO CONTRIBUTE
    CallForPresentations : * PRE-CONFERENCE WORKSHOPS
    CallForPresentations : * 30-MINUTE PODIUM PRESENTATIONS
    CallForPresentations : * HOW TO SUBMIT A PROPOSAL
    CallForPresentations : * REVIEW PROCESS AND NOTIFICATIONS
    CallForPresentations : * QUESTIONS

    Sponsorship : - Description
    Sponsorship : - link to sponsorship pdf
    Sponsorship : - button to sponsorship registration

    Program *-- Session
    Program : - Detailed Schedule

    Session : - Title
    Session : - Description
    Session : - Tags
    Session o-- Presenter

    Presenter : - Name
    Presenter : - Title


```
