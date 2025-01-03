otj-pmd-rulesets changelog
==========================

7.0.3
-----
* Several rules changed their names (to remove their junit specific naming)

7.0.2
----
* AvoidSynchronizedStatement is excluded. It's a stupid rule, put in to help
people not run afoul of Virtual Threads, but... it's just a bad rule.

7.0.1
-----
* Fine tuning false positives: drop SimplifyBooleanReturns, UnusedLocalVariable,ExceptionAsFlowControl,UselessQualifiedThis, UseExplicitTypes
* Remove unused rule ExcessiveMethodLength
* Avoid pulling in unndeeded dependencies, making the tree as trim as possible

7.0.0
-----
* For PMD 7 compatibility - should NOT be used with PMD < 7

1.2.8
-----
* Customize AvoidDuplicateLiterals to be less annoying

1.2.7
-----
* InvalidSlf4jMessageFormat rule no longer used in PMD, and causes nasties.

1.2.6
-----
* Exclude UnnecessaryFullyQualifiedName

1.2.5
-----
* Exclude AvoidUncheckedExceptionsInSignatures

1.2.4
-----
* Exclude UseUnderscoresInNumericLiterals

1.2.3
-----
* Add a couple exceptions for PMD 6.7.0

1.2.2
-----
* converted rule set to modern PMD 6.5.0 engine format

1.2.0
-----
* open source!

1.1.1
-----
* Exclude AccessorMethodGeneration rule

1.1.0
-----
* Exclude many of the more annoying PMD rules

1.0.1
-----
* Initial not-totally-broken release
