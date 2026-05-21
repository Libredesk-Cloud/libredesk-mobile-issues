# [](https://github.com/Libredesk-Cloud/libredesk-mobile/compare/v0.2.6...v) (2026-05-21)


### Bug Fixes

* **auth:** redirect to AppStatesInitializationMiddleware after login ([e95d7ab](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/e95d7abd49948bfee4d17bc8b90aa46895302eb1))
* **conversation:** replace infinite while loop with InstantTimer, cancel on dispose ([65ea360](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/65ea36004263247c23fb580a439157aa223d0a5b))
* **menu-popup:** simplify status update action sequence ([2142113](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/2142113b8490667e6123949a4d2ad91624040b46))
* **navbar:** replace infinite while loop with InstantTimer, cancel on dispose ([c30a8ef](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/c30a8ef98c0f28382932eaecc7fa13656eef57f5))
* **state:** wrap app state lists in LoggableList consistently ([a6dfd34](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/a6dfd34ab0e2b73c2220e99f9f23202ec3de36ba))
* **struct:** use snake_case key created_at in StatusStruct ([00944ad](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/00944ad014650b405e35b3051a9ff34991aab9a1))


### Features

* **actions:** add getAppVersion custom action ([4f4769c](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/4f4769c85df0a044ed92f80e5c26a84e410f6be5))
* **conversation:** add ConversationReadInactive component ([dd45245](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/dd452451f98fd1626c3faa7ff676d8f5a880da4a))
* **conversation:** add MenuPopup component for status update ([56c7750](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/56c775043f46048f948f5059a9bdd593ed5917c2))
* **conversation:** integrate MenuPopup in conversation screen header ([49ec5da](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/49ec5daf9cd2a24931d76c8d745bed0367c2f594))
* **conversation:** poll MarkConversationLastSeen every 15s on screen load ([5eee01c](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/5eee01c759ceaf999bcc3c71c345ad90f3777726))
* **flutter_flow:** add InstantTimer utility for cancellable periodic actions ([c04065f](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/c04065fe279de611fb9ad230b6682dd44214e1c7))
* **middleware:** add RouteAware mixin and debug lifecycle hooks ([7bab1d1](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/7bab1d1e2d4c1ff483e87e95f48e74c81b0b2449))
* **middleware:** implement AppStatesInitialization with loading progress ([7fc3e00](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/7fc3e00f0dc8037c374402f3fb1fc0de8b382469))
* **nav:** add AppStatesInitializationMiddleware route and export ([2822678](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/282267879cb51d34f1725c5aa31d24ba38b5c8a9))


### Reverts

* Revert "chore(ios): remove manual code signing settings from Podfile post_install" ([23be13b](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/23be13b259f9c39669366bb45056b9e926797fbd))
