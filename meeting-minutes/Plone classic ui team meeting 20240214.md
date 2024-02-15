# Plone classic ui team meeting 14.02.2024

Discord Classic UI voice and video channel:
https://discord.com/channels/786421998426521600/862359284422410302

Put meeting minutes here, after the meeting: https://github.com/plone/classic-ui-team/tree/main/meeting-minutes

## Participants:
-   @stevepiercy
-   @mrtango
-   @thet
-   @erral
-   @petschki

## Classic UI Project Board

-   https://github.com/orgs/plone/projects/28

## Topics to discuss:

-   [Plone Tagung](https://plonetagung.de/2024/)
    -   working on JBOT (deprecation feature) during sprint
        - Extend ZCML
    -   Classic UI to Static Site talk by @MrTango
-   Plone competition @MrTango 
    -   One bigger german Plone agency moved away from Plone (Volto) and to Wagtail + nextjs
    -   We have to learn more from our friends in Drupal and TYPO3
        - put more energy in Plone distributions, this was the main driver for Drupal, nobody installs a vanilla Drupal
        - TYPO3 became the new base for the Government Site Builder platform in Germany     
-   [Google Season of Docs draft proposal](https://gist.github.com/stevepiercy/ae3b0ef94e4e92f496a03c2f2df97e03). @stevepiercy
    -   Feedback wanted.
    -   Stipends available for participants.
    -   @Maik asks Jan Ulrich Hasecke if he is interested in participating as professional technical writer.
-   Documentation updates @stevepiercy
    -   [Install](https://6.docs.plone.org/install/index.html)
    -   [First-time contributors](https://6.docs.plone.org/contributing/first-time.html)
    -   [Image handling](https://6.docs.plone.org/classic-ui/images.html#scaling-mode)
    -   Still need lots of 5.2 docs to be migrated.
        -   [Migrate buildout.coredev docs into Plone 6 Documentation](https://github.com/plone/documentation/issues/1486)
        -   [Migrate plone.app.dexterity docs into Plone 6 Documentation](https://github.com/plone/documentation/issues/1445)
-   Framework Team status and coordination with other teams: @erral
    -   Instead of having a meeting for the sake of having a meeting, the Framework Team will have ad hoc meetings to discuss and resolve issues. Contact each of the relevant team leads to call an ad hoc meeting.
    -   Maik suggests having someone from IMIO in the meetings because of their work on Classic. @erral will try to get them on-board.
-   Review Documentation PR https://deploy-preview-1547--6-docs-plone-org.netlify.app/guides/classic-ui/working-with-content/index.html @petschki -> plonetagung
-   Plone 6.1a1
    -   plone.app.z3cform 4.4.x improvements
        -   https://6.docs.plone.org/backend/widgets.html
        -   https://6.docs.plone.org/backend/fields.html
        -   https://6.docs.plone.org/backend/schemas.html
        -   https://6.docs.plone.org/backend/content-types/index.html
    -   mockup/staticresource maintenance
-   Discussed about https://github.com/plone/Products.CMFPlone/pull/3844 caching problems - @petschki will rethink this at the plonetagung with @tlotze

