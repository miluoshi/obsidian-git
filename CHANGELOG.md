# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [1.21.1](https://github.com/denolehov/obsidian-git/compare/1.21.0...1.21.1) (2022-02-19)


### Bug Fixes

* better automatic backup/pull description ([10c3072](https://github.com/denolehov/obsidian-git/commit/10c307228da5c79cf62acfa2d6c90d2f519855a8)), closes [#181](https://github.com/denolehov/obsidian-git/issues/181)
* catch more git errors ([153fd82](https://github.com/denolehov/obsidian-git/commit/153fd82d7467d6c58905fa77c4376b2e79594810))
* stage filenames with leading '-' ([c06296e](https://github.com/denolehov/obsidian-git/commit/c06296e364962474299687e941fcdab8e03c9061)), closes [#184](https://github.com/denolehov/obsidian-git/issues/184)

### [1.21.0](https://github.com/denolehov/obsidian-git/compare/1.20.1...1.20.2) (2022-02-02)


### Bug Fixes

* stage files in vault below git root ([9d3c662](https://github.com/denolehov/obsidian-git/commit/9d3c6620f32b392935a689a9ff645aa664f49478)), closes [#172](https://github.com/denolehov/obsidian-git/issues/172)

### Features

* new sync method ([f1d6b33](https://github.com/denolehov/obsidian-git/commit/f1d6b334972b76271a15883c31784812f24d6878))

### [1.20.1](https://github.com/denolehov/obsidian-git/compare/1.20.0...1.20.1) (2022-01-29)


### Bug Fixes

* show correct debug console hotkey ([087582e](https://github.com/denolehov/obsidian-git/commit/087582e429d96345c1f1ee17e0d6a1eeb71d9489)), closes [#175](https://github.com/denolehov/obsidian-git/issues/175)

## [1.20.0](https://github.com/denolehov/obsidian-git/compare/1.19.0...1.20.0) (2022-01-08)


### Features

* :sparkles: Add "Open File in GitHub" Command, fix [#149](https://github.com/denolehov/obsidian-git/issues/149) ([2c216d0](https://github.com/denolehov/obsidian-git/commit/2c216d033fe0a82a68cf4951d72b5af4e9d10c87))
* :sparkles: Add Command to open file history on GitHub ([e7dd288](https://github.com/denolehov/obsidian-git/commit/e7dd288ba85a87e783d18c2b51e9027ec20f94fa))
* :sparkles: Add Diff View ([78cd43f](https://github.com/denolehov/obsidian-git/commit/78cd43fadece2b2d6bed80582bba18d842632e1a)), closes [#158](https://github.com/denolehov/obsidian-git/issues/158)
* :sparkles: Add Folder view to Sidebar ([919dc44](https://github.com/denolehov/obsidian-git/commit/919dc4435f08e8b3217ee66237a0671687bdb5a1)), closes [#134](https://github.com/denolehov/obsidian-git/issues/134)
* :sparkles: Allow multiline commit messages, fix [#157](https://github.com/denolehov/obsidian-git/issues/157) ([80ea17e](https://github.com/denolehov/obsidian-git/commit/80ea17e34f07f43bfe2aef1b5c520160a0e71e10))
* Add toggle in Settings to choose default layout ([38c7240](https://github.com/denolehov/obsidian-git/commit/38c7240918d1e463044431d976b9025eb1fdc318))


### Bug Fixes

* :bug: Fix RegEx for openInGitHub ([ca59a2d](https://github.com/denolehov/obsidian-git/commit/ca59a2db581643cfd77f3663850fe1243efe4260))
* :children_crossing: Show diff on double click ([407dcc0](https://github.com/denolehov/obsidian-git/commit/407dcc05d6e9679c7487c1d2dfa78f580c16b5da))
* catch diff for deleted file ([710cd2c](https://github.com/denolehov/obsidian-git/commit/710cd2cc6e69c1561277c762518ba0ba903e91f3))
* different tree data structure ([0fd2f95](https://github.com/denolehov/obsidian-git/commit/0fd2f954b66f0336475f8babb1904130711cbc50))
* many minor fixes ([7d29bef](https://github.com/denolehov/obsidian-git/commit/7d29bef4ed7793b399a704f73a3ab458e043e595))
* refresh source control view on change ([45e54e2](https://github.com/denolehov/obsidian-git/commit/45e54e21d097492d35084e4b7c52e1f7df5c59b1))
* remove tree structure from settings ([5af00ae](https://github.com/denolehov/obsidian-git/commit/5af00ae593d573016694da3bc9bbb218c8baa978))

## [1.19.0](https://github.com/denolehov/obsidian-git/compare/1.18.1...1.19.0) (2021-12-22)


### Features

* add rebase option for pull ([b04e444](https://github.com/denolehov/obsidian-git/commit/b04e444e99ca31d1abb1e4bfdd81cbdaca88caec)), closes [#155](https://github.com/denolehov/obsidian-git/issues/155)

### [1.18.1](https://github.com/denolehov/obsidian-git/compare/1.18.0...1.18.1) (2021-12-09)


### Bug Fixes

* use more specific css class ([471b257](https://github.com/denolehov/obsidian-git/commit/471b257671b861f69747882fcd67be22f7dca287))

## [1.18.0](https://github.com/denolehov/obsidian-git/compare/1.17.0...1.18.0) (2021-12-09)


### Features

* add commands for push and commit ([82dd037](https://github.com/denolehov/obsidian-git/commit/82dd037189a4dbe1b8ef7cad13d0c11b0817af2d)), closes [#122](https://github.com/denolehov/obsidian-git/issues/122)
* use icons for status bar ([96dcbc4](https://github.com/denolehov/obsidian-git/commit/96dcbc443369803a6f11d69ca80f34176025864a)), closes [#147](https://github.com/denolehov/obsidian-git/issues/147)


### Bug Fixes

* show error notices for a longer time ([d455489](https://github.com/denolehov/obsidian-git/commit/d45548993bcb95924a28f723d616e6c2f8c7c293)), closes [#148](https://github.com/denolehov/obsidian-git/issues/148)

## [1.17.0](https://github.com/denolehov/obsidian-git/compare/1.16.2...1.17.0) (2021-12-08)


### Features

* add hostname commit message placeholder ([32d8382](https://github.com/denolehov/obsidian-git/commit/32d8382c804b1e86effb409246dad06cad78506d)), closes [#146](https://github.com/denolehov/obsidian-git/issues/146)


### Bug Fixes

* clear autobackup/pull correctly ([1c5eeab](https://github.com/denolehov/obsidian-git/commit/1c5eeab098609ab5925a2ddda3aeef76db2660b3))
* don't start autobackup with 0 interval time ([a36c741](https://github.com/denolehov/obsidian-git/commit/a36c741cb1a5e557615768af3656dc76d6391ed0))

### [1.16.2](https://github.com/denolehov/obsidian-git/compare/1.16.1...1.16.2) (2021-11-29)


### Bug Fixes

* don't use new auto backup after change by default ([cc95a96](https://github.com/denolehov/obsidian-git/commit/cc95a96613386c30c379457d7d33198808403c63))

### [1.16.1](https://github.com/denolehov/obsidian-git/compare/1.16.0...1.16.1) (2021-11-28)


### Bug Fixes

* proper utf-8 encoding ([1bc7d28](https://github.com/denolehov/obsidian-git/commit/1bc7d2844ec3b3a954abe3c11766fd1e2d1c1b2a)), closes [#121](https://github.com/denolehov/obsidian-git/issues/121)

## [1.16.0](https://github.com/denolehov/obsidian-git/compare/1.15.1...1.16.0) (2021-11-28)


### Features

* add auto backup after last change ([192a947](https://github.com/denolehov/obsidian-git/commit/192a9474af7fbd607d451c8b95afaa46c84b7a9d)), closes [#140](https://github.com/denolehov/obsidian-git/issues/140)

### [1.15.1](https://github.com/denolehov/obsidian-git/compare/1.15.0...1.15.1) (2021-11-25)


### Bug Fixes

* use custom git binary path for git check ([7188753](https://github.com/denolehov/obsidian-git/commit/718875300f6f9d22e8773a5336bd70b095f63845))

## [1.15.0](https://github.com/denolehov/obsidian-git/compare/1.14.3...1.15.0) (2021-11-11)


### Features

* add custom commit message to auto backup ([b3d8077](https://github.com/denolehov/obsidian-git/commit/b3d8077bab29edf2602cd57a392969abf89e4241)), closes [#135](https://github.com/denolehov/obsidian-git/issues/135)

### [1.14.3](https://github.com/denolehov/obsidian-git/compare/1.14.2...1.14.3) (2021-11-03)

### Bug Fixes

* open file from Git view when no other file is opened

### [1.14.2](https://github.com/denolehov/obsidian-git/compare/1.14.1...1.14.2) (2021-11-01)


### Bug Fixes

* replace '?' by 'U' for untracked files ([64cf162](https://github.com/denolehov/obsidian-git/commit/64cf1623e50513f0f46141f6860650d0a865238c))
* wrap tooltip for long paths ([1fc4c1f](https://github.com/denolehov/obsidian-git/commit/1fc4c1fd7afbdbb08d7e3a061dd5d602e6f195a3))

### [1.14.1](https://github.com/denolehov/obsidian-git/compare/1.14.0...1.14.1) (2021-11-01)


### Bug Fixes

* list files in commit body ([f52a18b](https://github.com/denolehov/obsidian-git/commit/f52a18b3a3b6b05d643541baf2f74c32bb3e88d4)), closes [#131](https://github.com/denolehov/obsidian-git/issues/131)

## [1.14.0](https://github.com/denolehov/obsidian-git/compare/1.13.1...1.14.0) (2021-10-31)


### Features

* New Git view in the sidebar to stage and commit individual files. Thanks to @phibr0 for making the UI


### [1.13.1](https://github.com/denolehov/obsidian-git/compare/1.13.0...1.13.1) (2021-09-30)


### Bug Fixes

* changed files path was wrong with whitespaces ([043f02f](https://github.com/denolehov/obsidian-git/commit/043f02f89daea8051612b5f7816564ba7f7657e8)), closes [#119](https://github.com/denolehov/obsidian-git/issues/119)

## [1.13.0](https://github.com/denolehov/obsidian-git/compare/1.12.0...1.13.0) (2021-09-21)


### Features

* support cloning remote repos ([ab5ece7](https://github.com/denolehov/obsidian-git/commit/ab5ece75ceba3af5845770dc029732d5657720a3))

## [1.12.0](https://github.com/denolehov/obsidian-git/compare/1.11.0...1.12.0) (2021-09-18)


### Features

* support custom git binary path ([7793035](https://github.com/denolehov/obsidian-git/commit/77930351622a86ef3babdb4d60acbc8ff334cc84)), closes [#113](https://github.com/denolehov/obsidian-git/issues/113)

## [1.11.0](https://github.com/denolehov/obsidian-git/compare/1.10.2...1.11.0) (2021-09-15)


### Features

* add remote editing ([f70363b](https://github.com/denolehov/obsidian-git/commit/f70363b522c2e144260411d01e26108f7dedb735))
* support initalizing a new repo ([0fd2062](https://github.com/denolehov/obsidian-git/commit/0fd20627c3c289a05e0aba179b36badfe11d2414))
* support selecting upstream branch ([013878e](https://github.com/denolehov/obsidian-git/commit/013878e378bdbc6bab23c94615fba0c2bb72e1dc))

### [1.10.2](https://github.com/denolehov/obsidian-git/compare/1.10.1...1.10.2) (2021-09-05)


### Bug Fixes

* plugin status bar now displays time from last update (push or pull) ([b835fc3](https://github.com/denolehov/obsidian-git/commit/b835fc3548884dca4084ec37a296ebebf9c9dab7))

### [1.10.1](https://github.com/denolehov/obsidian-git/compare/1.10.0...1.10.1) (2021-08-19)


### Bug Fixes

* checkRequirements cant find user.name/email ([1994a44](https://github.com/denolehov/obsidian-git/commit/1994a44c5ecec121965505e2627d26460425e4dd))
* rename commands to be more consistend ([5e07e80](https://github.com/denolehov/obsidian-git/commit/5e07e80a13640b6ba587185880ba01befbd563ac))

## [1.10.0](https://github.com/denolehov/obsidian-git/compare/1.9.3...1.10.0) (2021-08-11)


### Features

* add submodules support ([2a4ce6d](https://github.com/denolehov/obsidian-git/commit/2a4ce6d47696cd6667b639c8479b37f61346e9be)), closes [#93](https://github.com/denolehov/obsidian-git/issues/93)


### Bug Fixes

* Changed the branchLocal command to branch with no-color ([dbd93cf](https://github.com/denolehov/obsidian-git/commit/dbd93cfe5f127874a514837577b42b34a07bcf3e))

### [1.9.3](https://github.com/denolehov/obsidian-git/compare/1.9.2...1.9.3) (2021-07-13)


### Bug Fixes

* storing lastAutos in a file caused many problems ([2812d94](https://github.com/denolehov/obsidian-git/commit/2812d948f0c6b0534c507425249c93397f71e973)), closes [#90](https://github.com/denolehov/obsidian-git/issues/90) [#78](https://github.com/denolehov/obsidian-git/issues/78)

### [1.9.2](https://github.com/denolehov/obsidian-git/compare/1.9.1...1.9.2) (2021-05-12)


### Bug Fixes

* plugin started wrong when normally enabled ([dc9c4b1](https://github.com/denolehov/obsidian-git/commit/dc9c4b13387067793e315a9aca24c05c75fb6d38))
* storing of last auto backup/pull caused merge conflicts ([cf6f279](https://github.com/denolehov/obsidian-git/commit/cf6f27900d05eb3ffe74222950cd00270879fd6c)), closes [#74](https://github.com/denolehov/obsidian-git/issues/74)

### [1.9.1](https://github.com/denolehov/obsidian-git/compare/1.9.0...1.9.1) (2021-05-07)


### Bug Fixes

* init slowed Obsidian startup time down ([e3f559c](https://github.com/denolehov/obsidian-git/commit/e3f559c14b54ef97eb8d07397d8b92250eeb3d62)), closes [#72](https://github.com/denolehov/obsidian-git/issues/72)

## [1.9.0](https://github.com/denolehov/obsidian-git/compare/1.8.1...1.9.0) (2021-05-02)


### Features

* add env var OBSIDIAN_GIT for scripting ([2b76097](https://github.com/denolehov/obsidian-git/commit/2b7609774cfd8689297c23ea672264cea6255409))
* add option to disable status bar ([0ab55d3](https://github.com/denolehov/obsidian-git/commit/0ab55d3f0805a031e9e3ec5b5cfa21d8c5026330)), closes [#70](https://github.com/denolehov/obsidian-git/issues/70)
* auto pull/backup outlives session ([7ec00e7](https://github.com/denolehov/obsidian-git/commit/7ec00e7cfd113aeb827f282d765ca061d85235a6)), closes [#68](https://github.com/denolehov/obsidian-git/issues/68)

### [1.8.1](https://github.com/denolehov/obsidian-git/compare/1.8.0...1.8.1) (2021-04-12)


### Bug Fixes

* add promise queue ([f95d71a](https://github.com/denolehov/obsidian-git/commit/f95d71a5475107dbf1bbacfb3bdb4e74fd190d15)), closes [#61](https://github.com/denolehov/obsidian-git/issues/61)

## [1.8.0](https://github.com/denolehov/obsidian-git/compare/1.7.0...1.8.0) (2021-03-31)


### Features

* open not supported files in changed files modal in default app ([93930e0](https://github.com/denolehov/obsidian-git/commit/93930e079384d0ae2ed165e94241dc1d0acee82a))

## [1.7.0](https://github.com/denolehov/obsidian-git/compare/1.6.1...1.7.0) (2021-03-24)


### Features

* add git initialization and conflict files status to statusbar ([ba0ef11](https://github.com/denolehov/obsidian-git/commit/ba0ef11a5abcc8ff11d9e33ca8157a283d06920b))
* auto pull on specified interval ([2aa7fb8](https://github.com/denolehov/obsidian-git/commit/2aa7fb866e41c1f7170b723a35d9acd2942921b0)), closes [#59](https://github.com/denolehov/obsidian-git/issues/59)
* conflict files support ([358dc6e](https://github.com/denolehov/obsidian-git/commit/358dc6e492e6ef8156687535d14a9070ebadfb30)), closes [#38](https://github.com/denolehov/obsidian-git/issues/38)
* list changed files ([5e28b94](https://github.com/denolehov/obsidian-git/commit/5e28b9449f3f7f978fe825fb102b61fb27d191e4))


### Bug Fixes

* conflict files pane was opened on pull error ([8d43e7b](https://github.com/denolehov/obsidian-git/commit/8d43e7b32e7b5082c3518537ce32c0627b35dfb2))

### [1.6.1](https://github.com/denolehov/obsidian-git/compare/1.6.0...1.6.1) (2021-03-17)


### Bug Fixes

* disable check for root git repository ([49a68e0](https://github.com/denolehov/obsidian-git/commit/49a68e0396b46c09a49f03898b804f97d1a709b3)), closes [#55](https://github.com/denolehov/obsidian-git/issues/55) [#11](https://github.com/denolehov/obsidian-git/issues/11)

## [1.6.0](https://github.com/denolehov/obsidian-git/compare/1.5.0...1.6.0) (2021-03-15)


### Features

* commit changes with specified message ([e992199](https://github.com/denolehov/obsidian-git/commit/e9921994e135ac01f5eda8f23d7c4db312cedd05)), closes [#26](https://github.com/denolehov/obsidian-git/issues/26)
* list filenames affected by commit in the commit body ([0ce9ac3](https://github.com/denolehov/obsidian-git/commit/0ce9ac310c402a3a7a679fc30e591a045d3a4fb2)), closes [#3](https://github.com/denolehov/obsidian-git/issues/3)
* pull before push ([30d8798](https://github.com/denolehov/obsidian-git/commit/30d8798d433f080404bd22c8a33a1ea49b37648f)), closes [#43](https://github.com/denolehov/obsidian-git/issues/43)


### Bug Fixes

* does not push when no changes detected ([d016dee](https://github.com/denolehov/obsidian-git/commit/d016dee92db4af02446b112de580b5197a3303f3)), fixes [#33](https://github.com/denolehov/obsidian-git/issues/33)
* git repository check ([98fa9f7](https://github.com/denolehov/obsidian-git/commit/98fa9f758f9b08546c0c9319a14fd25b85af4503))
* initialization procedure ([1d71418](https://github.com/denolehov/obsidian-git/commit/1d714181d8967fa6089cd380b879ce652332a3fa)), fixes [#27](https://github.com/denolehov/obsidian-git/issues/27)
* lastUpdate gets changed when no changes are detected ([71d2a59](https://github.com/denolehov/obsidian-git/commit/71d2a59f1d5ea7f7fd08e77b1802a47d0aae3f46))
* needed tracking branch to commit ([619c5d1](https://github.com/denolehov/obsidian-git/commit/619c5d182e95c5f1ca946c56d8c002e6b3f09daf))

## [1.5.0](https://github.com/denolehov/obsidian-git/compare/v1.2.0...v1.5.0) (2020-12-08)


### Features

* add {{files}} template placeholder ([64adf0f](https://github.com/denolehov/obsidian-git/commit/64adf0f464cfdad544fec225e52798ccbb565d4d))
* add option to toggle pushing to remote


### Bug Fixes

* change "auto push" setting to "disable push" to resolve issues with obsidian settings not loading correctly ([e00014c](https://github.com/denolehov/obsidian-git/commit/e00014cb269efa6391ebeb1d1e0026d209635bfe))
* correctly update `.lastUpdate` timestamp during push/pull ([4b61297](https://github.com/denolehov/obsidian-git/commit/4b61297be84fa7940e2909ddfdd2ef1d8608e20d))
* fix plugin getting stuck at "checking repo status.." message ([4875519](https://github.com/denolehov/obsidian-git/commit/4875519f9986946f0628a343c8ffd94686b86fa4))
* fix status bar messages race conditions ([f3f0a63](https://github.com/denolehov/obsidian-git/commit/f3f0a63132e0cd38c27d0e14c08a8b7c59134a83))

## [1.4.0](https://github.com/denolehov/obsidian-git/compare/v1.3.0...v1.4.0) (2020-11-01)


### Features

* display messages in status bar (including error ones) ([e1e0fcc](https://github.com/denolehov/obsidian-git/commit/e1e0fcc26d5736637239316d5881a696f78eca30))

## [1.3.0](https://github.com/denolehov/obsidian-git/compare/v1.2.0...v1.3.0) (2020-10-31)


### Features

* add `{{numFiles}}` placeholder ([fbc6ce8](https://github.com/denolehov/obsidian-git/commit/fbc6ce85d4f6f2b183c7a41f9cbd8f2814027e92))
* add more granular customization of `{{date}}` commit message placeholder ([7063f5a](https://github.com/denolehov/obsidian-git/commit/7063f5a902c3141671ddbf3c82c2076e07cc872b))

## [1.2.0](https://github.com/denolehov/obsidian-git/compare/v1.1.0...v1.2.0) (2020-10-31)


### Features

* `master` branch is no longer hardcoded ([dc8f3bd](https://github.com/denolehov/obsidian-git/commit/dc8f3bda9751a358fdd64771eec0c6b25bb07f6d))
* allow specifying `{{date}}` placeholder in commit message ([43c5f6e](https://github.com/denolehov/obsidian-git/commit/43c5f6e509d1284411ff26332b7820710fd51c2f))
* rename "Autosave" to "Vault backup interval" ([26cd1e3](https://github.com/denolehov/obsidian-git/commit/26cd1e371ad5b7076ac1da7575983ba4f6791713))


### Bug Fixes

* fix `undefined` backup settings and rearrange settings a bit ([68f8b84](https://github.com/denolehov/obsidian-git/commit/68f8b8438c9aba3c314ee2baa857bfd1efd587d2))
* register interval functions so Obsidian properly unloads them ([717a538](https://github.com/denolehov/obsidian-git/commit/717a53811ef55907ca804ead83d7db6a4747199f))
* save settings on plugin unload ([67cd7a3](https://github.com/denolehov/obsidian-git/commit/67cd7a3f9303505b86b6399694bf1d8e4c8bff4e))

## [1.1.0](https://github.com/denolehov/obsidian-git/compare/v1.0.0...v1.1.0) (2020-10-29)


### Features

* Add "Disable notifications" setting + some minor fixes ([ec240a7](https://github.com/denolehov/obsidian-git/commit/ec240a7122656e551b93a79ad5af9b7be138b2ec))
* Add an option to automatically fetch updates from remote repository when Obsidian starts ([aa59d29](https://github.com/denolehov/obsidian-git/commit/aa59d29fb23ac5b42d8c6a644fdc413a04931966))
* Add status bar that shows status updates ([80dbf0f](https://github.com/denolehov/obsidian-git/commit/80dbf0f647fe27237bd86174feebe7987a90be63))

## [1.0.0](https://github.com/denolehov/obsidian-git/compare/v0.0.6...v1.0.0) (2020-10-27)


### Bug Fixes

* update some Notice messages ([a97c44e](https://github.com/denolehov/obsidian-git/commit/a97c44e2f5a1581e5bb8ea432deca108df8c7fde))

### [0.0.6](https://github.com/denolehov/obsidian-git/compare/v0.0.5...v0.0.6) (2020-10-27)


### Features

* Add autosave feature ([6f0d6bc](https://github.com/denolehov/obsidian-git/commit/6f0d6bc0b8b84fe6e14fcf1c85e6a6213c9da578))

### [0.0.5](https://github.com/denolehov/obsidian-git/compare/v0.0.4...v0.0.5) (2020-10-27)


### Features

* Add an ability to specify custom commit message (specified in plugin settings) ([ca67112](https://github.com/denolehov/obsidian-git/commit/ca671124c5b2dc5127b76f48ab94e63d1e2b3626))

### [0.0.4](https://github.com/denolehov/obsidian-git/compare/v0.0.3...v0.0.4) (2020-10-27)


### Features

* Improve UX a bit by showing notification of what's happening when user presses hotkey ([c562e74](https://github.com/denolehov/obsidian-git/commit/c562e746d7538923a378104d0204dad1f3f2aa61))

### [0.0.3](https://github.com/denolehov/obsidian-git/compare/v0.0.2...v0.0.3) (2020-10-27)


### Features

* add an ability to push changes to a remote repository ([f229516](https://github.com/denolehov/obsidian-git/commit/f2295165fbd77dd9ed6e4cdd2f6d085b3ee78bfe))

### [0.0.2](https://github.com/denolehov/obsidian-git/compare/v0.0.1...v0.0.2) (2020-10-27)


### Features

* Add an ability to pull changes from remote repository. ([88da6e5](https://github.com/denolehov/obsidian-git/commit/88da6e5bc01ef5066ab994e69640e0e101ed6b8f))

### 0.0.1 (2020-10-27)
