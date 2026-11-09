# Umbraco CMS 13.x Upgrade - Accumulated Changes

This document contains all changes (breaking, non-breaking, new features, bug fixes) accumulated from versions 13.3.3 to the current up to date minor version.


## Version 13.4.0

### Changes
Release notes were not published on GitHub for this release. Please refer to Umbraco's official issue tracker or blog for version 13.4.0.

### Full Details

N/A - GitHub release missing.

---

## Version 13.4.1

### Changes
Release notes were not published on GitHub for this release. Please refer to Umbraco's official issue tracker or blog for version 13.4.1.

### Full Details

N/A - GitHub release missing.

---

## Version 13.5.0

### Changes
Release notes were not published on GitHub for this release. Please refer to Umbraco's official issue tracker or blog for version 13.5.0.

### Full Details

N/A - GitHub release missing.

---

## Version 13.5.1

### Changes
Release notes were not published on GitHub for this release. Please refer to Umbraco's official issue tracker or blog for version 13.5.1.

### Full Details

N/A - GitHub release missing.

---

## Version 13.5.2

### Changes
Release notes were not published on GitHub for this release. Please refer to Umbraco's official issue tracker or blog for version 13.5.2.

### Full Details

N/A - GitHub release missing.

---

## Version 13.5.3

### Changes
Release notes were not published on GitHub for this release. Please refer to Umbraco's official issue tracker or blog for version 13.5.3.

### Full Details

N/A - GitHub release missing.

---


## Version 13.6.0

[Release 13.6.0 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.6.0)

### New Features / Additions
* Content.EditorDirectiveController: added formSubmittedValidationFailed broadcast to prevent fields to stay disabled by @Yinzy00 in https://github.com/umbraco/Umbraco-CMS/pull/17018
* v13.5 - New Swedish translation crashes Umbraco, removed duplicate areas. by @madsoulswe in https://github.com/umbraco/Umbraco-CMS/pull/17059
* Added fix for <umb-button-group /> label issues by @abjerner in https://github.com/umbraco/Umbraco-CMS/pull/15409
* Added integration test to verify the Delivery API contract by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/17949
* add missing new media auditTrail translation by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/17981
* Added a maxlength setting to the regular expression pattern field by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/17982
* V13 QA added parallelization for E2E tests by @andr317c in https://github.com/umbraco/Umbraco-CMS/pull/17995
## New Contributors

### Bug Fixes
* Templates can still be editable when using runtime mode Production bug fixed  #16622 by @nick-hoang in https://github.com/umbraco/Umbraco-CMS/pull/16923
* Fix: V13 ensure data change is detected on embedding media (16806) by @nielslyngsoe in https://github.com/umbraco/Umbraco-CMS/pull/17008
* Fix null reference exception in CacheValues.For when building the CompositeStringStringKey by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/17024
* Update ImageSharpMiddlewareOption for fixing invalid width and height by @NguyenThuyLan in https://github.com/umbraco/Umbraco-CMS/pull/17126
* Fixed issue #17225. Extended RTE valid element configuration by @wwrobel in https://github.com/umbraco/Umbraco-CMS/pull/17227
* Fix greedy Install url detection by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/17241
* Fix ContentStore locking exceptions in async code by @ronaldbarendse in https://github.com/umbraco/Umbraco-CMS/pull/17246
* Fix for #17187, unlock form after unsuccessful save and publish by @JasonElkin in https://github.com/umbraco/Umbraco-CMS/pull/17285
* Issue 17128 - Fix GetMediaByPath when querying for media which has been uploaded with dimensions in the file name by @justin-nevitech in https://github.com/umbraco/Umbraco-CMS/pull/17314
* V13/bugfix/fix infinite editor stuck in create action 15945 by @ealse in https://github.com/umbraco/Umbraco-CMS/pull/16280
* Fix RTE console error when blocks are not available by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/17582
* Fix `PanicException: failed to get child with id=` after updating content types by @ronaldbarendse in https://github.com/umbraco/Umbraco-CMS/pull/17702
* V13 Fixes #17646 where bold markdown does not work in a property description  by @danlister in https://github.com/umbraco/Umbraco-CMS/pull/17806
* Fix null exceptions when requesting specific content trough the backoffice APIs by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/17846
* Fix: only fire event when instance is available (issue 17847) by @nielslyngsoe in https://github.com/umbraco/Umbraco-CMS/pull/17987
* Fix: Do not re-map schedule modal on error as it leads to broken bindings by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/17990

### Full Details

## What's Changed
* Templates can still be editable when using runtime mode Production bug fixed  #16622 by @nick-hoang in https://github.com/umbraco/Umbraco-CMS/pull/16923
* Avoid concurrent build of `Umbraco.JsonSchema` tool and add execution timeouts to `Exec` build tasks by @ronaldbarendse in https://github.com/umbraco/Umbraco-CMS/pull/17006
* No longer shows success message if content moving is cancelled by @miguelcrpinto in https://github.com/umbraco/Umbraco-CMS/pull/15051
* Fix: V13 ensure data change is detected on embedding media (16806) by @nielslyngsoe in https://github.com/umbraco/Umbraco-CMS/pull/17008
* Content.EditorDirectiveController: added formSubmittedValidationFailed broadcast to prevent fields to stay disabled by @Yinzy00 in https://github.com/umbraco/Umbraco-CMS/pull/17018
* Fix null reference exception in CacheValues.For when building the CompositeStringStringKey by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/17024
* v13.5 - New Swedish translation crashes Umbraco, removed duplicate areas. by @madsoulswe in https://github.com/umbraco/Umbraco-CMS/pull/17059
* Update ImageSharpMiddlewareOption for fixing invalid width and height by @NguyenThuyLan in https://github.com/umbraco/Umbraco-CMS/pull/17126
* Fixed issue #17225. Extended RTE valid element configuration by @wwrobel in https://github.com/umbraco/Umbraco-CMS/pull/17227
* Fix greedy Install url detection by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/17241
* Fix ContentStore locking exceptions in async code by @ronaldbarendse in https://github.com/umbraco/Umbraco-CMS/pull/17246
* Updated image sharp to a non vulnerable version by @bergmania in https://github.com/umbraco/Umbraco-CMS/pull/17290
* Fix for #17187, unlock form after unsuccessful save and publish by @JasonElkin in https://github.com/umbraco/Umbraco-CMS/pull/17285
* V13: Use updated form components in the login form by @iOvergaard in https://github.com/umbraco/Umbraco-CMS/pull/17281
* MNTP: Improve site and root context for dynamic root by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/17303
* MNTP: Re-initialize contextual dialog options upon content creation by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/17301
* Issue 17128 - Fix GetMediaByPath when querying for media which has been uploaded with dimensions in the file name by @justin-nevitech in https://github.com/umbraco/Umbraco-CMS/pull/17314
* V10 updated message pack by @andr317c in https://github.com/umbraco/Umbraco-CMS/pull/17320
* V13 Updated version of messagepack by @andr317c in https://github.com/umbraco/Umbraco-CMS/pull/17321
* V13 QA Updated login tests to match locator by @andr317c in https://github.com/umbraco/Umbraco-CMS/pull/17334
* Include create date in audit item by @nikolajlauridsen in https://github.com/umbraco/Umbraco-CMS/pull/17447
* Use TryParse when parsing ID from claims by @Oxygen-cl in https://github.com/umbraco/Umbraco-CMS/pull/17414
* Add swiss languages as backoffice languages by @marwaldv in https://github.com/umbraco/Umbraco-CMS/pull/17177
* Block settings unavailable element type by @bjarnef in https://github.com/umbraco/Umbraco-CMS/pull/16328
* TinyMCE readonly mode by @bjarnef in https://github.com/umbraco/Umbraco-CMS/pull/17551
* Don't shrink crops container on right side by @bjarnef in https://github.com/umbraco/Umbraco-CMS/pull/16827
* Run both cms and package migrations in upgrader by @nikolajlauridsen in https://github.com/umbraco/Umbraco-CMS/pull/17575
* Added fix for <umb-button-group /> label issues by @abjerner in https://github.com/umbraco/Umbraco-CMS/pull/15409
* V13/bugfix/fix infinite editor stuck in create action 15945 by @ealse in https://github.com/umbraco/Umbraco-CMS/pull/16280
* Fix RTE console error when blocks are not available by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/17582
* Sort manifest file paths alphabetically by @mattbrailsford in https://github.com/umbraco/Umbraco-CMS/pull/14466
* Handle "all slashes" routes by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/17596
* Add cache key to GetByUserName by @Zeegaan in https://github.com/umbraco/Umbraco-CMS/pull/17350
* V13: Dropzone, upload complete callback with processed file array by @leekelleher in https://github.com/umbraco/Umbraco-CMS/pull/17631
* Revert #14234 add update error message for DB connection failures by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/17612
* Add ASCII file name conversion by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/17580
* V13: Lead char gets removed when reopening a link in the rich text editor by @iOvergaard in https://github.com/umbraco/Umbraco-CMS/pull/17667
* Fix `PanicException: failed to get child with id=` after updating content types by @ronaldbarendse in https://github.com/umbraco/Umbraco-CMS/pull/17702
* Updated NuGet Packages for v13 by @bergmania in https://github.com/umbraco/Umbraco-CMS/pull/17704
* Add "user info" endpoint for the Delivery API by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/17719
* Warn about un-routable content at publish time by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/17705
* Add (un)publishing details to TreeChange notifications by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/17757
* Make sure Examine dashboard still functions when an index is corrupt by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/17800
* V13 Fixes #17646 where bold markdown does not work in a property description  by @danlister in https://github.com/umbraco/Umbraco-CMS/pull/17806
* V13: Clear username cache by @Zeegaan in https://github.com/umbraco/Umbraco-CMS/pull/17815
* V13: Allow anonymous calls for `UmbLoginStatusController.HandleLogout` action by @elit0451 in https://github.com/umbraco/Umbraco-CMS/pull/17807
* Fix null exceptions when requesting specific content trough the backoffice APIs by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/17846
* V13: Add rcl files to static files tree by @Zeegaan in https://github.com/umbraco/Umbraco-CMS/pull/17671
* Make the Delivery API "ancestors" selector work with preview by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/17938
* Corrected property names and structure used in JSON schema generation for configuration of default data to install. by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/17946
* Added integration test to verify the Delivery API contract by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/17949
* V13 QA updated locator for failing E2E test by @andr317c in https://github.com/umbraco/Umbraco-CMS/pull/17825
* Allow filtering for multiple content types by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/17960
* V13: Show validation error, when saving invalid media by @Zeegaan in https://github.com/umbraco/Umbraco-CMS/pull/17961
* Improve YSOD rendering in the client by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/17940
* V13: Update @umbraco-ui/uui to 1.12.2 by @iOvergaard in https://github.com/umbraco/Umbraco-CMS/pull/17972
* Add Vary header to all content API operations by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/17962
* Resets send to approval dialog on close such that when re-opening the selection and operation can still be triggered. by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/17956
* V13: Update @microsoft/signalr from 7.0.12 to 8.0.7 by @iOvergaard in https://github.com/umbraco/Umbraco-CMS/pull/17973
* add missing new media auditTrail translation by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/17981
* Enforce the "Save and preview" button after when switching content app by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/17985
* Make the RTE handle inline elements gracefully for JSON by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/17983
* Fix: only fire event when instance is available (issue 17847) by @nielslyngsoe in https://github.com/umbraco/Umbraco-CMS/pull/17987
* Do not show "Save and preview" by default by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/17986
* Fix: Do not re-map schedule modal on error as it leads to broken bindings by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/17990
* Added a maxlength setting to the regular expression pattern field by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/17982
* V13 QA added parallelization for E2E tests by @andr317c in https://github.com/umbraco/Umbraco-CMS/pull/17995
* Add NoopCurrentMemberClaimsProvider so Umbraco can boot without the Delivery API enabled by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/18049
* V13: remove unused parameters and documentation by @iOvergaard in https://github.com/umbraco/Umbraco-CMS/pull/18095

## New Contributors
* @nick-hoang made their first contribution in https://github.com/umbraco/Umbraco-CMS/pull/16923
* @wwrobel made their first contribution in https://github.com/umbraco/Umbraco-CMS/pull/17227
* @Oxygen-cl made their first contribution in https://github.com/umbraco/Umbraco-CMS/pull/17414

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.5.3...release-13.6.0

---

## Version 13.7.0

[Release 13.7.0 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.7.0)

### New Features / Additions
* Added Resharper test assemblies to exclude list on TypeFinder by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18145
* Show notifications menu only to users with permission for the feature by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18184
* Fix issues in newly added buttongroup localization by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/18254
## New Contributors

### Bug Fixes
* Fix create child issue in list view with infinite editor (#13355). by @mvennevold in https://github.com/umbraco/Umbraco-CMS/pull/17637
* Fix out of memory file upload of 2gb+ files introduced by #14657 SVG xss by @TimBoonstra in https://github.com/umbraco/Umbraco-CMS/pull/17421
* V13: Fix members while using basic auth. by @nikolajlauridsen in https://github.com/umbraco/Umbraco-CMS/pull/18206
* Fix 11643 by @nielslyngsoe in https://github.com/umbraco/Umbraco-CMS/pull/18257
* Fixed userResource request to get all users by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18105

### Full Details

## What's Changed Since 13.7.0-rc

There have been no further updates since the [13.7.0-rc release](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.7.0-rc).

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.7.0-rc...release-13.7.0

## What's Changed Since The Previous Release (13.6.0)

* Lucene Package Update to Address CVE-2024-43383 by @amsclark in https://github.com/umbraco/Umbraco-CMS/pull/17942
* Allow skipSelect blueprints only when one blueprint exists by @callumbwhyte in https://github.com/umbraco/Umbraco-CMS/pull/17818
* Fix create child issue in list view with infinite editor (#13355). by @mvennevold in https://github.com/umbraco/Umbraco-CMS/pull/17637
* Replaced deprecated navigator.platform with navigator.userAgent for platform detection. by @manutdkid77 in https://github.com/umbraco/Umbraco-CMS/pull/17373
* Handles migration case where an expected constraint is renamed but the constraint does not exist by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18063
* Add clientside validation to webhook events by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/18089
* Make it possible to reset media picker crops by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/18110
* Redirect to the published URL when exiting preview by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/18114
* Added Resharper test assemblies to exclude list on TypeFinder by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18145
* Do not allow editing read-only properties by clicking their labels by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/18152
* Provides an option to remove the inessential version number from the generated models by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18081
* Excluded tags from trashed content by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18164
* More robust resolving of Delivery API redirects by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/18160
* Fix out of memory file upload of 2gb+ files introduced by #14657 SVG xss by @TimBoonstra in https://github.com/umbraco/Umbraco-CMS/pull/17421
* Update auth.element.ts by @garpunkal in https://github.com/umbraco/Umbraco-CMS/pull/18192
* Enforce user start nodes for media uploads through the RTE by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/18204
* Show notifications menu only to users with permission for the feature by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18184
* V13: Fix members while using basic auth. by @nikolajlauridsen in https://github.com/umbraco/Umbraco-CMS/pull/18206
* Set Smidge cachebuster type by @SimonHartfield in https://github.com/umbraco/Umbraco-CMS/pull/18198
* Cache null dictionary values by key by @callumbwhyte in https://github.com/umbraco/Umbraco-CMS/pull/15576
* Review: Allow Duplicate Email for Members by @jasont0101 in https://github.com/umbraco/Umbraco-CMS/pull/16202
* Fix issues in newly added buttongroup localization by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/18254
* Fix 11643 by @nielslyngsoe in https://github.com/umbraco/Umbraco-CMS/pull/18257
* Add validation to prevent update of a user or member to an invalid username (13) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18261
* Avoid an exception on sign out when the principal is populated from an incomplete external login by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18078
* Prevents folder selection in media picker when used from the multi URL picker by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18288
* URL encodes member user names when passing information for public access setting such that those with user names as emails containing a plus will be included in the rule by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18142
* Fixed userResource request to get all users by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18105
* Backport use of thread delay over sleep and handle dispose in FileSystemMainDomLock by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18151

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.6.0...release-13.7.0

## New Contributors
* @amsclark made their first contribution in https://github.com/umbraco/Umbraco-CMS/pull/17942
* @mvennevold made their first contribution in https://github.com/umbraco/Umbraco-CMS/pull/17637
* @TimBoonstra made their first contribution in https://github.com/umbraco/Umbraco-CMS/pull/17421
* @SimonHartfield made their first contribution in https://github.com/umbraco/Umbraco-CMS/pull/18198
* @jasont0101 made their first contribution in https://github.com/umbraco/Umbraco-CMS/pull/16202



---

## Version 13.7.1

[Release 13.7.1 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.7.1)

### New Features / Additions
## New Contributors

### Full Details

## Changes

### Security updates
- Improper API access control allows low-privilege users access to data type functionality - [Advisory GHSA-6ffg-mjg7-585x](https://github.com/umbraco/Umbraco-CMS/security/advisories/GHSA-6ffg-mjg7-585x)
- Restricted editor user can delete media item or access unauthorized content - [Advisory GHSA-wx5h-wqfq-v698](https://github.com/umbraco/Umbraco-CMS/security/advisories/GHSA-wx5h-wqfq-v698)
- Updated ImageSharp dependency to patched version following [CVE-2025-27598](https://www.cve.org/CVERecord?id=CVE-2025-27598)

## New Contributors
* @RolandKock made their first contribution in https://github.com/umbraco/Umbraco-CMS/pull/18602

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.7.0...release-13.7.1

---

## Version 13.7.2

[Release 13.7.2 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.7.2)

### Bug Fixes
### 🐛 Bug Fixes

### Full Details

## Changes

### 🐛 Bug Fixes
* Avoids collection was modified issue when flowing identities to the authenticated user's principal  @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18527

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.7.1...release-13.7.2

---

## Version 13.8.0

[Release 13.8.0 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.8.0)

### New Features / Additions
### 🚀 Backported Features

### Bug Fixes
### 🐛 Bug Fixes
### 🐛 Bug Fixes
* Fixed typo in TinyMCE's da.js by @abjerner in https://github.com/umbraco/Umbraco-CMS/pull/18628
* Fix issue text overflow when user name is too long by @NguyenThuyLan in https://github.com/umbraco/Umbraco-CMS/pull/18653
* Fixes issue with macro rendering in an RTE when GUIDs are used for backoffice document routes by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18691
* Hotfix sqlserver integration tests by @andr317c in https://github.com/umbraco/Umbraco-CMS/pull/18744

### Full Details

## What's Changed Since 13.8.0-rc

### 🐛 Bug Fixes

* Ignore endpoint selection candidates with host attribute if request doesn't match the configured hosts by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18820
* Check we have matched a preview URL by ID when exiting preview by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18841

## What's Changed Since The Previous Release (13.7.2)

### 📦 Dependencies
* build(deps): bump @umbraco-ui/uui from 1.12.2 to 1.13.0 by @iOvergaard in https://github.com/umbraco/Umbraco-CMS/pull/18830
* Updates dependency on Examine to 3.7 by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18676

### 🚀 Backported Features
* Split force for publish descendants into separate options for publish unpublish and re-publish unedited (13) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18249
* Reverts UI updates from publish with descendants dialog by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18647
* Backport `ShowUnroutableContentWarnings` to V13 by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/18479

### 🐛 Bug Fixes
* HTML encodes the user's name in the invite email by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18343
* Only filter post retrieval of entities for start nodes if working with entities that support start nodes by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18287
* Avoid exception when attempting to find member by Id when Id is not an expected Guid or integer, as can be the case with external member providers by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18320
* Disable webhook firing if disable in configuration (13) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18383
* Handle multiline statements in migrations by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18478
* Remove version from models builder generated code header when configured to do so by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18501
* Fixed typo in TinyMCE's da.js by @abjerner in https://github.com/umbraco/Umbraco-CMS/pull/18628
* Introduce publishNotifications method on IMembershipMemberService by @Zeegaan in https://github.com/umbraco/Umbraco-CMS/pull/18207
* Fix issue text overflow when user name is too long by @NguyenThuyLan in https://github.com/umbraco/Umbraco-CMS/pull/18653
* Render folders before files in static files picker by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18701
* Fixes issue with macro rendering in an RTE when GUIDs are used for backoffice document routes by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18691
* Hotfix sqlserver integration tests by @andr317c in https://github.com/umbraco/Umbraco-CMS/pull/18744

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.7.2...release-13.8.0

---

## Version 13.8.1

[Release 13.8.1 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.8.1)

### Changes
**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.8.0...release-13.8.1

### Full Details

### 🔒 Security updates
- Prevented possibility of user enumeration feasible based on timing of login response - [Advisory GHSA-4g8m-5mj5-c8xg](https://github.com/umbraco/Umbraco-CMS/security/advisories/GHSA-4g8m-5mj5-c8xg)

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.8.0...release-13.8.1

---

## Version 13.9.0

[Release 13.9.0 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.9.0)

### New Features / Additions
* Added custom RichTextRegexValidator to validate markup instead of JSON by @tomvanenckevort in https://github.com/umbraco/Umbraco-CMS/pull/19045
## New Contributors

### Bug Fixes
### 🐛 Bug Fixes
* Fix null member edge case by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/19463
### 🐛 Bug Fixes
* V13: attempted fix for Datepicker v13 issue #16008 by @Navya-Sinhaa in https://github.com/umbraco/Umbraco-CMS/pull/18903
* attempted fix for Save and Preview button #15360 by @Navya-Sinhaa in https://github.com/umbraco/Umbraco-CMS/pull/19138
* Fix root path regression for the Delivery API by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/19216
* Fix for block grid styling regression issue #15973 by @Lili-Rossiter in https://github.com/umbraco/Umbraco-CMS/pull/19014
* V13/bugfix/partial cache by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/19314
* Fixed check for navigation to list after delete of member by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19364

### Full Details

## What's Changed Since 13.9.0-rc

### 🐛 Bug Fixes
* Fix null member edge case by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/19463

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.9.0-rc...release-13.9.0

## What's Changed Since The Previous Release (13.8.1)

### 📦 Dependencies
* Upgrade examine to 3.7.1 by @dawoe in https://github.com/umbraco/Umbraco-CMS/pull/19186

### 🐛 Bug Fixes
* Move database cache rebuild to a background task with polling (13) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/18922
* V13: attempted fix for Datepicker v13 issue #16008 by @Navya-Sinhaa in https://github.com/umbraco/Umbraco-CMS/pull/18903
* Handle file paths as not found in delivery API by route requests by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19063
* attempted fix for Save and Preview button #15360 by @Navya-Sinhaa in https://github.com/umbraco/Umbraco-CMS/pull/19138
* V13 QA updated pipeline for acceptance to avoid issue when installing playwright by @andr317c in https://github.com/umbraco/Umbraco-CMS/pull/19140
* V13: Clear Member Username Cache in Load Balanced Environments by @nikolajlauridsen in https://github.com/umbraco/Umbraco-CMS/pull/19191
* Fix root path regression for the Delivery API by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/19216
* `TimedScope` improvements and login duration clean-up by @ronaldbarendse in https://github.com/umbraco/Umbraco-CMS/pull/19243
* Handle existing RichTextEditorValue when parsing from markup or JSON structure by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19266
* Added custom RichTextRegexValidator to validate markup instead of JSON by @tomvanenckevort in https://github.com/umbraco/Umbraco-CMS/pull/19045
* Invalidate external login session on removal of provider (13) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19273
* add single blocklist delete by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/18073
* [V13] User notifications not sent correctly when having more than 400 users by @vantovic in https://github.com/umbraco/Umbraco-CMS/pull/18370
* Fix for block grid styling regression issue #15973 by @Lili-Rossiter in https://github.com/umbraco/Umbraco-CMS/pull/19014
* V13/bugfix/partial cache by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/19314
* V13 QA Updated linux test images to match actual by @andr317c in https://github.com/umbraco/Umbraco-CMS/pull/19309
* Avoids unnecessary additional domain save notification publishing when sorting an already sorted collection of domains by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19106
* Adds support for retrieval of data type references when data type is routed using a GUID by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19184
* User invite email fails if visited more than once without completing by @dchallener in https://github.com/umbraco/Umbraco-CMS/pull/17901
* Fixed check for navigation to list after delete of member by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19364

## New Contributors
* @Navya-Sinhaa made their first contribution in https://github.com/umbraco/Umbraco-CMS/pull/18903
* @vantovic made their first contribution in https://github.com/umbraco/Umbraco-CMS/pull/18370

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.8.1...release-13.9.0

---

## Version 13.9.1

[Release 13.9.1 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.9.1)

### Bug Fixes
### 🐛 Bug Fixes
* Fix issues with removal of user logins on change to external login provider configuration (13) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19511

### Full Details

## What's Changed

### 🐛 Bug Fixes
* Fix issues with removal of user logins on change to external login provider configuration (13) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19511

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.9.0...release-13.9.1

---

## Version 13.9.2

[Release 13.9.2 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.9.2)

### Changes
**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.9.1...release-13.9.2

### Full Details

### 🔒 Security updates
- Prevented Disclosure of Configured Password Requirements - [Advisory GHSA-pgvc-6h2p-q4f6](https://github.com/umbraco/Umbraco-CMS/security/advisories/GHSA-pgvc-6h2p-q4f6)

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.9.1...release-13.9.2

---

## Version 13.9.3

[Release 13.9.3 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.9.3)

### Bug Fixes
- Fixed issue where Delivery API allows for cached requests to be returned with an invalid API key - [GHSA-75vq-qvhr-7ffr](https://github.com/umbraco/Umbraco-CMS/security/advisories/GHSA-75vq-qvhr-7ffr)

### Full Details

### 🔒 Security updates
- Fixed issue where Delivery API allows for cached requests to be returned with an invalid API key - [GHSA-75vq-qvhr-7ffr](https://github.com/umbraco/Umbraco-CMS/security/advisories/GHSA-75vq-qvhr-7ffr)

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.9.2...release-13.9.3

---

## Version 13.10.0

[Release 13.10.0 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.10.0)

### New Features / Additions
* Fix: #18421 - Added Max Length validation to PropertyTypeBasic Alias by @danielhnelson in https://github.com/umbraco/Umbraco-CMS/pull/18427
* Removes unnecessary newlines from rich text as JSON delivery API output by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19391
## New Contributors

### Bug Fixes
### 🐛 Bug Fixes
* Fixed check for navigation to list after delete of member by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19364
* Fix issue with requests to delivery API by path where URL segment contains special characters by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19390
* Resolved exception thrown from NuCache locking mechanism on near-simultaneous content publish requests by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19434
* Fix pagination in Content Delivery API Index Helper by @Brynjarth in https://github.com/umbraco/Umbraco-CMS/pull/19606
* #16772 partial fix backoffice redirect after login by @kows in https://github.com/umbraco/Umbraco-CMS/pull/19663

### Full Details

## What's Changed Since 13.10.0-rc

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.10.0-rc...release-13.10.0

## What's Changed Since The Previous Release (13.9.3)

### 🐛 Bug Fixes
* Fix: #18421 - Added Max Length validation to PropertyTypeBasic Alias by @danielhnelson in https://github.com/umbraco/Umbraco-CMS/pull/18427
* Fixed check for navigation to list after delete of member by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19364
* Fix issue with requests to delivery API by path where URL segment contains special characters by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19390
* Removes unnecessary newlines from rich text as JSON delivery API output by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19391
* Lock appropriate tree for media operations by @rbottema in https://github.com/umbraco/Umbraco-CMS/pull/19422
* Resolved exception thrown from NuCache locking mechanism on near-simultaneous content publish requests by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19434
* Ensure tag operations are case insensitive on insert across database types by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19439
* Add a warning to the `CreateContentFromBlueprint` method xml docs by @lauraneto in https://github.com/umbraco/Umbraco-CMS/pull/19542
* Preserve word boundaries when indexing RTE content with <br> tags by @steveatkiss in https://github.com/umbraco/Umbraco-CMS/pull/19540
* Fix pagination in Content Delivery API Index Helper by @Brynjarth in https://github.com/umbraco/Umbraco-CMS/pull/19606
* Ensures that null values aren't used to create a CompositeStringStringKey by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19646
* #16772 partial fix backoffice redirect after login by @kows in https://github.com/umbraco/Umbraco-CMS/pull/19663
* Clear member cache by older user name when member user name is updated (13) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19672
* Register no-op implementation of IMemberPartialViewCacheInvalidator in headless setups by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19666
* Adds variation by the header name Accept-Language to the delivery API output cache policy by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19709
* Add support for programmatic creation of property types providing the data type key by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19720
* Parse update date before sorting in media list view by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19711
* Add defensive coding to the member application initializer by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/19760
* Retrieve only user external logins when invalidate following removal of backoffice external user login by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19766

### 🚤 Performance Optimizations
* Optimize the member save as part of the member login process, by-passing locking and audit steps and handling only the expected update properties by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19308

## New Contributors
* @danielhnelson made their first contribution in https://github.com/umbraco/Umbraco-CMS/pull/18427
* @steveatkiss made their first contribution in https://github.com/umbraco/Umbraco-CMS/pull/19540
* @Brynjarth made their first contribution in https://github.com/umbraco/Umbraco-CMS/pull/19606

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.9.3...release-13.10.0-rc

---

## Version 13.10.1

[Release 13.10.1 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.10.1)

### Changes
**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.10.0...release-13.10.1

### Full Details

### 🔒 Security updates
- Updated to use latest dependency of Smidge. Smidge 4.6 was recently released to handle [a reported vulnerability](https://github.com/asust9/smidge-vuln?tab=readme-ov-file) and Umbraco now has a dependency on this secured version.

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.10.0...release-13.10.1

---

## Version 13.11.0

[Release 13.11.0 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.11.0)

### New Features / Additions
## New Contributors

### Bug Fixes
### 🐛 Bug Fixes
* Caching: Fixes regression of the caching of null representations for missing dictionary items (closes #20336) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/20344
### 🐛 Bug Fixes
* Persistence: Fix issue with use of EF Core scopes within notification handlers (closes #18977) by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/19797

### Full Details

## What's Changed in 13.11.0

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.11.0-rc2...release-13.11.0

## What's Changed in 13.11.0-rc2

### 🐛 Bug Fixes

* Caching: Fixes regression of the caching of null representations for missing dictionary items (closes #20336) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/20344

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.11.0-rc...release-13.11.0-rc2

## What's Changed Since The Last Release (13.10.1)

### 🐛 Bug Fixes
* List views: The filter param should be URL encoded (closes #19773) by @AaronSadlerUK in https://github.com/umbraco/Umbraco-CMS/pull/19774
* Permissions: Content picker search with start node configured not taking user start nodes into account (closes #19432) by @lauraneto in https://github.com/umbraco/Umbraco-CMS/pull/19800
* Preview: Use a regex to filter our invalid culture codes rather than relying on the culture being installed on the operating system (closes #19817) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19821
* Authentication: Retain original backoffice location on login after timeout (closes #19971 and #20050 ) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/19984
* Delivery API: Support query string and anchor for local links in output by (closes #18475) @kjac in https://github.com/umbraco/Umbraco-CMS/pull/20142
* Migrations: Avoid throwing an exception on getting references when migrating content with changed data types (closes #19784) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/20079
* Engage: Adds property awareness to validation context to avoid potential infinite loops (closes #19654) by @cornehoskam in https://github.com/umbraco/Umbraco-CMS/pull/19827
* Engage: Make notification service able to handle segmented content (closes #20045) by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/20160
* Persistence: Fix issue with use of EF Core scopes within notification handlers (closes #18977) by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/19797

### 🌐 Localization
* Localization: Add Arabic (ar) backoffice translation by @wpplumber in https://github.com/umbraco/Umbraco-CMS/pull/19896

## New Contributors
* @wpplumber made their first contribution in https://github.com/umbraco/Umbraco-CMS/pull/19896

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.10.1...release-13.11.0-rc

---

## Version 13.12.0

[Release 13.12.0 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.12.0)

### New Features / Additions
* Backoffice Caching: Added cache buster for block list stylesheets (closes #20683) by @creativesuspects in https://github.com/umbraco/Umbraco-CMS/pull/20686
## New Contributors

### Bug Fixes
* Fixed dependency conflicts when installing Microsoft.EntityFrameworkCore.Design (closes #17839) by @lauraneto in https://github.com/umbraco/Umbraco-CMS/pull/20480
### 🐛 Bug Fixes
* UX: Fix overflow of `umb-editor-header` if the description is locked and too long by @rickbutterfield in https://github.com/umbraco/Umbraco-CMS/pull/20190
* Caching: Fixes regression of the caching of null representations for missing dictionary items (closes #20336 for 13) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/20344
* Configuration: Fixed integer overflow in setting MaxRequestBodySize and MultipartBodyLengthLimit by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/20348
* Repositories: UserService.GetAllInGroup fix by @piers-taylor-1994 in https://github.com/umbraco/Umbraco-CMS/pull/20425
* Grid (Legacy): Fix for RTE drag and drop issue (closes #16591) by @bhcoder in https://github.com/umbraco/Umbraco-CMS/pull/20498
* Fix memory leak with `IOptionsMonitor.OnChange` and non-singleton registered components (closes #20709)  by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/20722

### Full Details

## What's Changed in 13.12.0

### 📦 Dependencies
* Update ImageSharp to latest patch releases by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/20275
* Fixed dependency conflicts when installing Microsoft.EntityFrameworkCore.Design (closes #17839) by @lauraneto in https://github.com/umbraco/Umbraco-CMS/pull/20480
* Dependencies: Update dotnet sdk and node development dependency to latest secure version of current major by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/20729

### 🚀 Improvements
* Allow fetching multiple content and media by `Guid` and `Udi` by @bjarnef in https://github.com/umbraco/Umbraco-CMS/pull/15289
* Querying extensions: Allow `ContentAtRoot()` to accept culture by @bjarnef in https://github.com/umbraco/Umbraco-CMS/pull/20129
* Media Picker: Implement paging by @landlogicit in https://github.com/umbraco/Umbraco-CMS/pull/20202

### 🐛 Bug Fixes
* UX: Fix overflow of `umb-editor-header` if the description is locked and too long by @rickbutterfield in https://github.com/umbraco/Umbraco-CMS/pull/20190
* Link rendering: Add support for `UrlMode` parameter in `HtmlLocalLinkParser` by @rickbutterfield in https://github.com/umbraco/Umbraco-CMS/pull/20200
* Property editors: Ensure values no longer allowed as options in checkbox list configuration are removed from the value, such that they will be removed from the persisted data when saved by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/20208
* Prevent RTE being marked as dirty when content contains empty paragraph by @mcl-sz in https://github.com/umbraco/Umbraco-CMS/pull/20335
* Caching: Fixes regression of the caching of null representations for missing dictionary items (closes #20336 for 13) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/20344
* Configuration: Fixed integer overflow in setting MaxRequestBodySize and MultipartBodyLengthLimit by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/20348
* Repositories: UserService.GetAllInGroup fix by @piers-taylor-1994 in https://github.com/umbraco/Umbraco-CMS/pull/20425
* Members: Do not convert calculated lockedOutUntil time to UTC by @Migaroez in https://github.com/umbraco/Umbraco-CMS/pull/17007
* Grid (Legacy): Fix for RTE drag and drop issue (closes #16591) by @bhcoder in https://github.com/umbraco/Umbraco-CMS/pull/20498
* Notifications: Populate `IncludeDescendants` on `ContentPublishedNotification` when publishing branch by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/20578
* Backoffice Caching: Added cache buster for block list stylesheets (closes #20683) by @creativesuspects in https://github.com/umbraco/Umbraco-CMS/pull/20686
* Fix memory leak with `IOptionsMonitor.OnChange` and non-singleton registered components (closes #20709)  by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/20722

## New Contributors
* @bhcoder made their first contribution in https://github.com/umbraco/Umbraco-CMS/pull/20498

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.11.0...release-13.12.0

---

## Version 13.12.1

[Release 13.12.1 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.12.1)

### Changes
* Resolves vulnerability relating to the handling and deletion of temporary files during the dictionary and content type upload process discussed in https://github.com/umbraco/Umbraco-CMS/security/advisories/GHSA-hfv2-pf68-m33x.
**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.12.0...release-13.12.1

### Full Details

## What's Changed

### 🔒 Security
* Resolves vulnerability relating to the handling and deletion of temporary files during the dictionary and content type upload process discussed in https://github.com/umbraco/Umbraco-CMS/security/advisories/GHSA-hfv2-pf68-m33x.

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.12.0...release-13.12.1

---

## Version 13.13.0

[Release 13.13.0 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.13.0)

### Bug Fixes
### 🐛 Bug Fixes
* Media picker: Fix image selection after upload when media picker presents multiple pages (closes #21115) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/21117
* Members: Fix `GetLockoutEnd` to return `DateTimeOffSet` max rather than `DateTime` max (closes #21155) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/21157
### 🐛 Bug Fixes
* Redirects: Fix self referencing redirects for 13 (closes #20139) by @NillasKA in https://github.com/umbraco/Umbraco-CMS/pull/20908
* Media Picker Fixed folder navigation when returning from an empty folder (closes #20975) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/20987

### Full Details

## What's Changed Since 13.13.0-rc3

### 🐛 Bug Fixes

* Media picker: Fix image selection after upload when media picker presents multiple pages (closes #21115) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/21117
* Members: Fix `GetLockoutEnd` to return `DateTimeOffSet` max rather than `DateTime` max (closes #21155) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/21157

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.13.0-rc3...release-13.13.0

## What's Changed Since 13.13.0-rc2

### 📦 Dependencies
* Updates dependencies to latest patch for 13.13 by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/21108

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.13.0-rc2...release-13.13.0-rc3

## What's Changed Since 13.13.0-rc

### 🔒 Security
* Resolves vulnerability relating to the handling and deletion of temporary files during the dictionary and content type upload process released in 13.12.1 and discussed in https://github.com/umbraco/Umbraco-CMS/security/advisories/GHSA-hfv2-pf68-m33x.

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.13.0-rc...release-13.13.0-rc2

## What's Changed Since the Previous Release (13.12.0)

### 🐛 Bug Fixes

* Redirects: Fix self referencing redirects for 13 (closes #20139) by @NillasKA in https://github.com/umbraco/Umbraco-CMS/pull/20908
* Content picker: Allow selections on a content picker on a read-only document to be opened (closes #20816) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/20819
* Block Grid: Align read-only display with other property editors by @bjarnef in https://github.com/umbraco/Umbraco-CMS/pull/21007
* Content editing: Correct handling of read-only of name field when `A` action is removed in `SendingContentNotification` by @bjarnef in https://github.com/umbraco/Umbraco-CMS/pull/20072
* Content picker: Remove multi-node content picker entries by UDI to account for index not aligning with stored values (closes #20943) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/20950
* Content picker: Allow selections on a content picker on a read-only document to be opened (closes #20816) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/20819
* Media Picker Fixed folder navigation when returning from an empty folder (closes #20975) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/20987
* Media Picker: Present root nodes for users with more than one media root node assigned (closes #20967 and #21048) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/20993

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.12.0...release-13.13.0-rc

---

## Version 13.13.1

[Release 13.13.1 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.13.1)

### Bug Fixes
* Media Picker: Fix media picker folder navigation with "ignore user start nodes" enabled (closes #21840 for 13) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/21899

### Full Details

## What's Changed
* File Uploads: Remove legacy Windows path length checks and related tests by @ronaldbarendse in https://github.com/umbraco/Umbraco-CMS/pull/21884
* Media Picker: Fix media picker folder navigation with "ignore user start nodes" enabled (closes #21840 for 13) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/21899

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.13.0...release-13.13.1

---

## Version 13.14.0

[Release 13.14.0 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.14.0)

### Changes
**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.14.0-rc3...release-13.14.0
* Surface controllers: validate redirect URL in member operation surface controllers by @NguyenThuyLan in https://github.com/umbraco/Umbraco-CMS/pull/22565
**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.14.0-rc2...release-13.14.0-rc3
* Dependencies: Pin `System.Security.Cryptography.Xml` to resolve vulnerability warning (Umbraco 13) by @crixlis
**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.14.0-rc...release-13.14.0-rc2
* Backport optimisations on content type save from #21910 to V13 by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/22314
**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.13.1...release-13.14.0-rc

### Full Details

## What's Changed Since 13.14.0-rc3

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.14.0-rc3...release-13.14.0

## What's Changed Since 13.14.0-rc2

### 🔒 Security Hardening

* Surface controllers: validate redirect URL in member operation surface controllers by @NguyenThuyLan in https://github.com/umbraco/Umbraco-CMS/pull/22565

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.14.0-rc2...release-13.14.0-rc3

## What's Changed Since 13.14.0-rc1

### 📦 Dependencies

* Dependencies: Pin `System.Security.Cryptography.Xml` to resolve vulnerability warning (Umbraco 13) by @crixlis
in https://github.com/umbraco/Umbraco-CMS/pull/22513

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.14.0-rc...release-13.14.0-rc2

## What's Changed Since The Previous Version (13.13.1)

### 🚤 Performance

* Backport optimisations on content type save from #21910 to V13 by @kjac in https://github.com/umbraco/Umbraco-CMS/pull/22314

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.13.1...release-13.14.0-rc

---

## Version 13.15.0

[Release 13.15.0 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.15.0)

### Changes
**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.15.0-rc...release-13.15.0
* Upgrade Examine to 3.8.0 by @si25 in https://github.com/umbraco/Umbraco-CMS/pull/23075
**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.14.0...release-13.15.0-rc

### Full Details

## What's Changed Since 13.15.0-rc

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.15.0-rc...release-13.15.0

## What's Changed Since the Previous Version (13.14.0)

### 📦 Dependencies

* Upgrade Examine to 3.8.0 by @si25 in https://github.com/umbraco/Umbraco-CMS/pull/23075

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.14.0...release-13.15.0-rc

---

## Version 13.15.1

[Release 13.15.1 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.15.1)

### Changes
* Addressed vulnerability relating to expansion of property values relating to protected, picked content described in https://github.com/umbraco/Umbraco-CMS/security/advisories/GHSA-wr57-hqmp-fgvh
* Bumped MessagePack dependency to 2.5.302.
**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.15.0-rc...release-13.15.1

### Full Details

## What's Changed

### 🔒 Security

* Addressed vulnerability relating to expansion of property values relating to protected, picked content described in https://github.com/umbraco/Umbraco-CMS/security/advisories/GHSA-wr57-hqmp-fgvh

### 📦 Dependencies

* Bumped MessagePack dependency to 2.5.302.

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.15.0-rc...release-13.15.1

---

## Version 13.16.0

[Release 13.16.0 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.16.0)

### Breaking Changes
* Update MailKit dependency and resolve nullability breaking changes (for Umbraco 13) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/23306

### Full Details

## What's Changed

### 📦 Dependencies

* Update MailKit dependency and resolve nullability breaking changes (for Umbraco 13) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/23306

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.15.1...release-13.16.0

---

## Version 13.16.1

[Release 13.16.1 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.16.1)

### Changes
* Dependencies: Pin vulnerable transitive dependencies (`System.Security.Cryptography.Xml`, `SQLitePCLRaw.lib.e_sqlite3`, `Microsoft.Build.Tasks.Core`) by @NguyenThuyLan in https://github.com/umbraco/Umbraco-CMS/pull/23718
**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.16.0...release-13.16.1

### Full Details

## What's Changed
### 📦 Dependencies
* Dependencies: Pin vulnerable transitive dependencies (`System.Security.Cryptography.Xml`, `SQLitePCLRaw.lib.e_sqlite3`, `Microsoft.Build.Tasks.Core`) by @NguyenThuyLan in https://github.com/umbraco/Umbraco-CMS/pull/23718

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.16.0...release-13.16.1

---

## Version 13.16.2

[Release 13.16.2 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.16.2)

### Changes
* Bump JS diff and underscore versions for security patches by @jfrank-nih in https://github.com/umbraco/Umbraco-CMS/pull/23910
**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.16.1...release-13.16.2

### Full Details

## What's Changed

### 📦 Dependencies

* Bump JS diff and underscore versions for security patches by @jfrank-nih in https://github.com/umbraco/Umbraco-CMS/pull/23910

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.16.1...release-13.16.2

---

## Version 13.16.3

[Release 13.16.3 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.16.3)

### Bug Fixes
* Resolved backoffice users can grant user groups start nodes outside their own access (start node restriction bypass) from https://github.com/umbraco/Umbraco-CMS/security/advisories/GHSA-r4qv-c8pg-qq59

### Full Details

## What's Changed

### Security

### 🔒 Security
* Resolved backoffice users can grant user groups start nodes outside their own access (start node restriction bypass) from https://github.com/umbraco/Umbraco-CMS/security/advisories/GHSA-r4qv-c8pg-qq59

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.16.2...release-13.16.3

---

## Version 13.16.4

[Release 13.16.4 on GitHub](https://github.com/umbraco/Umbraco-CMS/releases/tag/release-13.16.4)

### Bug Fixes
> This release updates `SixLabors.ImageSharp` to 3.2.0 and `SixLabors.ImageSharp.Web` to 3.3.0 to take Six Labors' security fixes (#24339). These versions add a build-time licence check from Six Labors. Whether your project is affected depends on how it references ImageSharp:
* Bump SixLabors.ImageSharp to 3.2.0 and ImageSharp.Web to 3.3.0 for security fixes for Umbraco 13 (closes #24300) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/24339

### Full Details

## What's Changed

> [!WARNING]
> **ImageSharp licence check: Release builds can fail after upgrading**
>
> This release updates `SixLabors.ImageSharp` to 3.2.0 and `SixLabors.ImageSharp.Web` to 3.3.0 to take Six Labors' security fixes (#24339). These versions add a build-time licence check from Six Labors. Whether your project is affected depends on how it references ImageSharp:
>
> - **ImageSharp comes in only through Umbraco (or another package):** no change.
> - **Your project has a direct `PackageReference` to `SixLabors.ImageSharp` or `SixLabors.ImageSharp.Web`:** Release builds fail with "No Six Labors license found". Debug builds only warn, so you may not notice this until CI or publish.
> - **Your direct reference is pinned to an older version (for example 3.1.12):** restore fails with NU1605 (package downgrade). After you update the reference, the point above applies.
>
> To resolve this, either remove the direct reference if it only exists to pin a version (Umbraco still brings ImageSharp in, so its APIs stay available), or get a licence key from Six Labors. See [Security Support and License Enforcement](https://sixlabors.com/posts/security-support-and-license-enforcement/) for licence options. Sites using `Umbraco.Cms.Imaging.ImageSharp2` stay on ImageSharp 2.x and are not affected.

### 📦 Dependencies
* Bump SixLabors.ImageSharp to 3.2.0 and ImageSharp.Web to 3.3.0 for security fixes for Umbraco 13 (closes #24300) by @AndyButland in https://github.com/umbraco/Umbraco-CMS/pull/24339
* Update MessagePack and pin System.Security.Cryptography.Pkcs and .Xml to patched versions (v13) by @richarth in https://github.com/umbraco/Umbraco-CMS/pull/24298

**Full Changelog**: https://github.com/umbraco/Umbraco-CMS/compare/release-13.16.3...release-13.16.4

---
