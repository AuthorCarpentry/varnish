# varnish 0.1.16

* CHAPTERS has been temporarily renamed to EPISODES to reduce cognative load
  between the webpage and the source folders

# varnish 0.1.15

* The search field has been disabled to avoid confusion. We have not yet enabled
  search as this requires further testing. Disabling the search field means that
  it is now more clear that search is not yet available.
  (#44 by @zkamvar)

# varnish 0.1.14

* indicators for lesson development stage (pre-alpha, alpha, beta) have been 
  added as `<abbr>` elements with a link to the appropriate section in the CDH
  and `title` elements that describe the purpose of the stage. Visually hidden
  text follows the `<abbr>` element for users who can not perceive the lesson
  visually (#39 by @zkamvar, reviewed by @tobyhodges).
* FIX: .lesson-title and .lesson-title-md are now inline-block elements

# varnish 0.1.13

* An alert for the workbench beta phase is implemented if the lesson has
  `workbench-beta: true` in the `config.yaml`.

# varnish 0.1.12

* dropdown navigation no longer is hidden by the sidebar on XXL screens;
  z-index of `nav.bottom-nav` set to 3.
  (reported: #35 by @brownsarahm, fixed: #36 by @zkamvar)

# varnish 0.1.11
 
* blockquotes are now more clearly delineated from the rest of the content
  (reported: #27 by @fiveop, fixed: #31 by @zkamvar)

# varnish 0.1.10

* lab and incubator logos are now available.

# varnish 0.1.9

* Fix missing pegboard version tag

# varnish 0.1.8

* custom workbench engines are now properly linked in the footer via the 
  `sandpaper_cfg` `pegboard_cfg`, and `varnish_cfg` variables.
* code of conduct link now points to the `CODE_OF_CONDUCT.md` file so authors
  can update or modify their own code of conduct (NOTE: all Carpentries lessons
  MUST have a code of conduct that links to the Carpentries Code of Conduct as
  well as the reporting guidelines.

# varnish 0.1.7

* compile the changes from 0.1.6

# varnish 0.1.6

* Tables now scroll on overflow

# varnish 0.1.5

* The index page now has specific sections for schedule and setup that link to
  the `#schedule` and `#setup` anchors. This partially addresses 
  https://github.com/carpentries/sandpaper/issues/260

# varnish 0.1.4

* Removed " logo" suffix from the logo elements, as it is redundant
  https://webaim.org/techniques/alttext/#logos

# varnish 0.1.3

* Add small version of the carpentries logo

# varnish 0.1.2

* Add matmo analytics in the footer (@fmichonneau, #17)

# varnish 0.1.1

* Add LICENSE file clarifying MIT licensing

# varnish 0.1.0

* Breaking change; moving from the carpentries/styles theme to the new theme
  developed in 2021. Variables and layouts have changed significantly, so this
  package gains a significant update.

# varnish 0.0.0.9008

* instructor block placeholder added

# varnish 0.0.0.9007

* update css to use em and not px
* align logo with navbar
* add testing phase notification to navbar

# varnish 0.0.0.9006

* First tracked version of varnish
* updated links to engines in the footer
