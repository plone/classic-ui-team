# Plone classic ui team meeting 10.01.2024

Discord Classic UI voice and video channel:
https://discord.com/channels/786421998426521600/862359284422410302

## Participants:
-   @stevepiercy
-   @pbauer
-   @maurits
-   @thet
-   @DonThorHammer
-   @nikunjrohit


## Classic UI Project Board

-   https://github.com/orgs/plone/projects/28

## Topics to discuss:

-   Final call: updated Plone release policy [Maurits]
    
    -   https://docs.google.com/document/d/1NnWVCfXQzFlpZQZQKythpiBmID2_ycR_Ug-bozHYdqI/edit?usp=sharing will replace https://plone.org/download/release-schedule
    -   https://docs.google.com/spreadsheets/d/1xQvgkrzDBbx-eaQ6eSeUFsBe0CJRq_WmaQzzugUNCVQ/edit?usp=sharing is the source for the release graphic and the versions table.
    -   https://docs.google.com/document/d/1yVOL4MopTTGkTqYpcBORSowOlb3ebvTSiH7gQjZ_brg/edit?usp=sharing will replace https://plone.org/security/update-policy

-   Documentation top 4 open issues [Steve]
    -   [Clarify install methods to either "Create a project" or "Contribute to a package"](https://github.com/plone/documentation/issues/1598) Feedback wanted!
    -   [Create a Contributing to Plone section](https://github.com/plone/documentation/issues/1278)
    -   [Migrate buildout.coredev docs into Plone 6 Documentation](https://github.com/plone/documentation/issues/1486)
    -   [Migrate plone.app.dexterity docs into Plone 6 Documentation](https://github.com/plone/documentation/issues/1445)
-   Other Documentation issues [Steve]
    -   Production vs. Development installation
    -   Customizing Barceloneta theme
    -   Customizing Mockup
    -   PLIP requirement: write docs.

-   Time Zone PLIP for 6.1 or 6.2 WIP [Steve]
    -   Cannot set events with a user preferred time zone:
        -   [Volto #5324](https://github.com/plone/volto/issues/5324)
        -   [plone.org #141](https://github.com/plone/plone.org/issues/141)
    -   Cannot set events with a user preferred time zone:
        [plone.org #151](https://github.com/plone/plone.org/issues/151)
    -   Event Content Type Overhaul [Volto #5551](https://github.com/plone/volto/issues/5551)
    -   Fixed utc problems in RecurrenceWidget [Volto #5002]
    -   Date and Time inputs should continue to use HTML5 inputs.
    -   Add `<date>` and `<time>` HTML markup for date and time values when displayed.
    -   Ensure that Publish and Expiration Dates have times.
    -   Upgrade steps need to be considered for all objects that have a date or time.

-   [Google Season of Docs](https://developers.google.com/season-of-docs/) topics? [Steve]

-   Possible PLIPS for 6.1/6.2
    -   Use better semantic HTML in Plone (`<time>`, `<address>`)
    -   Remove AtD settings from TinyMCE settings.
    
-   [Plone Tagung](https://plonetagung.de/2024/). Sprints to get Momentum for Plone 6.1.
    
-   We mentioned `plone.classicui` package.
    It would be nice to have all the templates in one place.
    
