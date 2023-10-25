# Plone classic ui team meeting 25.10.2023

## Report of PloneConf

Maurits, reported a bit from PloneConf and also idea for released 6.0 and 6.1.
Ongoing decoupling of Packages in core.

Release policy and roadmap needs to be discussed on the Plone Community Forum so that everyone is paddling this boat in the same direction. This includes our support policy. It needs to be published on plone.org. In particular, what version of Volto will the released cookiecutter use, and what do you need to put into Plone 6 Documentation? Maurits, Victor, and Timo are leading this effort.

Many details need to be discussed about the future direction of Classic UI, and this should be fed into the Plone Release Schedule, Support Policy, and Roadmap. Who needs to be involved in this detailed discussion?

Participants:
-   @mrtango
-   @jensens
-   @petschki

Topics:
-   Move templates
-   JBOT
-   See the section "Template aliasing/deprecation" below

## `plone.app.contenttypes`

@Gotcha working on https://github.com/plone/plone.app.contenttypes/pull/676
Improve tabular view customizability.
To be decided where this can be merged, probably 6.1/2.


## First-time contributors

Although Classic UI has not been flooded with newbies, Steve wants to get feedback from the Classic UI Team, as any policy decision and guidance will affect all of Plone.

-   [Volto Team meeting notes](https://docs.google.com/document/d/1nZV6AI-6hGA-7Trceq2n_iA2M8C1ZBUA6hGAeBGG16Y/edit#heading=h.89f5yqzhczcn)
-   Documentation pull request: [Update first-time contributors per Volto Team discussion](https://github.com/plone/documentation/pull/1556)
-   [Pull request preview](https://deploy-preview-1556--6-docs-plone-org.netlify.app/contributing/first-time.html)


## Documentation progress

-   New page [Backend > Widgets](https://6.docs.plone.org/backend/widgets.html), thanks to @rber474 in [Adds backend widgets content fixing #1307](https://github.com/plone/documentation/pull/1552).
-   Schemas, Fields, Forms MrTango is working those chapters
-   WIP [Integrate Mockup's documentation](https://github.com/plone/documentation/pull/1548)
-   [WIP: Working With Content as new Classic UI user guide](https://github.com/plone/documentation/pull/1547)
-   Open Classic UI [Issues](https://github.com/plone/documentation/issues?q=is%3Aopen+is%3Aissue+label%3A%2299+tag%3A+classic-ui%22)
-   Open Classic UI [Pull Request](https://github.com/plone/documentation/pulls?q=is%3Aopen+is%3Aissue+label%3A%2299+tag%3A+classic-ui%22)

## Documentation structure

-  Idea: https://diataxis.fr/
-  example: https://docs.readthedocs.io/en/stable/

Having How-to Guides section in `/guides` on docs.plone.org with sub sections for Volto, Classic-UI and Backend would be good.
Volto has already started on this in a long running feature branch (https://github.com/plone/volto/tree/docs-reorg) against which new PRs (such as https://github.com/plone/volto/pull/5334) are made.

```
/guides
    /volto
    /classic-ui
    /backend
```


## Template aliasing/deprecation

trying to get in touch with the `z3c.jbot` or `zope.deferredimport` contributors to get an idea how to solve deprecating and moving templates to different packages without breaking too much.

After that we can start moving templates to `plone.classicui` package and decouple more Classic-UI stuff from core.

https://github.com/plone/plone.classicui/issues/7

- petschki


## Mockup updates

- TinyMCE 6 -> targets Plone 6.1, compatible with Plone 6.0
