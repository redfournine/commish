# `commish` Changelog


## 0.1.1 (07/16/2018)

* Introduced default Rake task to define CI process.
* Added `ruby-2.3.7`, `ruby-2.4.4` and `ruby-2.5.1` as test environment targets for TravisCI.
* Added CodeClimate maintainability badge.
* Moved `CHANGELOG` to `/docs` directory.
* Converted `LICENSE` to markdown.


## 0.1.0 (07/16/2018)

* Initial project release.
* Rules correspond to cops / settings available in RubCop `0.57`.
* Derivations from RuboCop defaults:
  - Layout/AlignHash (table formatted)
  - Layout/BlockAlignment (start of line)
  - Layout/ClassStructure (enabled, _assuming some additional tweaks_)
  - Layout/EmptyLineAfterGuardClause (enabled)
  - Layout/FirstArrayElementLineBreak (enabled)
  - Layout/FirstHashElementLineBreak (enabled)
  - Layout/MultilineAssignmentLayout (enabled)
  - Lint/InheritExcpetion (enforce `StandardError`)
  - Lint/NumberConversion (enabled)
  - Metrics/BlockLength (_exclusions_)
  - Metrics/LineLength (max: 120)
  - Style/AutoResourceCleanup (enabled)
  - Style/CollectionMethods (enabled)
  - Style/ImplicitRuntimeError (enabled)
  - Style/MethodCalledOnDoEndBlock (enabled)
  - Style/OptionHash (enabled)
  - Style/ReturnNil (enabled)
  - Style/Send (enabled)
  - Style/StringMethods (enabled)