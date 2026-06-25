# [](https://github.com/Libredesk-Cloud/libredesk-mobile/compare/v0.3.2...v) (2026-06-25)


### Bug Fixes

* **chat:** revert maxLines to 0 when text is expanded ([8744f5c](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/8744f5c39b45e5ca2e5a98059bd420050ae331fe))
* **chat:** use null instead of 0 for unlimited maxLines when expanded ([54bd5cd](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/54bd5cd82f06bbc7bdaf29ffd3cda2d5355f568c))
* **chat:** use static placeholder for agent name display ([50f2fda](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/50f2fda6906714db298e3a22cf786f6a024db1bd))
* **conversation:** pass ConversationStruct to MenuPopup ([33ff7f8](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/33ff7f8223569afc76f6ae27274c218bf078bbf6))
* **forms:** update model field initializers ([82d1741](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/82d1741180a9c307b8f62d316fca33e858b05880))
* **upload:** wrap media source picker in SafeArea ([861dd9c](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/861dd9c9816b02699e1fe87e3d81e6b88ac48281))


### Features

* **chat:** add reply icon button and fix text expansion layout ([a7052e1](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/a7052e11305a1820b6ca26d4cec77c7b8e0bade2))
* **chat:** wire reply button to ReplyForm bottom sheet; add conversation param ([0a7c78a](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/0a7c78adcbeb9033fdd98050a617a1cb477839b3))
* **conversation:** refactor chat message rendering and conversation screen ([697a60d](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/697a60d4d20a2e1c55d01fc7047b0bad86c7d63d))
* **conversations:** refresh list on page dispose ([f31a385](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/f31a385b663d40cf1e643ac30d85028a1d113d46))
* **navbar:** add fade transition and isComingFromEmailBox param to navigation ([4aff9e6](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/4aff9e695c941794f93b34dc84102e6a31fb7db6))
* **reply:** add ReplyForm component ([4d0b7d4](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/4d0b7d481becdf015fd058a01b2e92383e853c97))
* **reply:** add ReplyLongPressPopup component ([cd82d38](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/cd82d38a866a4bfd2bb225ffc2e4d32540fc09d2))
* **reply:** implement sendReply action block and wire form submission ([8acccc1](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/8acccc1d6ffd9b8bff1f597f03b5da1d94443cf4))
* **schema:** add SenderType enum and type MessageStruct.senderType ([a0415bc](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/a0415bc7f5e79733b01609da5673a941b6af6231))


### Reverts

* **conversations:** remove on-dispose list refresh ([1f75046](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/1f750465e0f8d41af134829b710e5b3c6d2e129e))
* **upload:** remove SafeArea wrapper from media source picker ([edc8689](https://github.com/Libredesk-Cloud/libredesk-mobile/commit/edc8689857b8ed1b73f8ce190d7196ef8b3154e1))
