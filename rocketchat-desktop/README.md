Rocket.Chat
===========

Rocket.Chat with patch from <https://github.com/RocketChat/Rocket.Chat.Electron/pull/1954>, fixes <https://github.com/RocketChat/Rocket.Chat.Electron/issues/1934>.

It seems that `nodejs-lts-erbium` is required to build Rocket.Chat instead of `nodejs` to prevent some strange failure while building.
