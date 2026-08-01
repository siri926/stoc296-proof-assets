# STOC-296 — final UI proof evidence index

| | |
|---|---|
| Final commit | `b2a41b40b74328ac4ec79a144e3b2941cd52e931` |
| Proof CI run | [`30716544536`](https://github.com/toloka-partners/a-vc-stock-visor/actions/runs/30716544536) (mobile-native.yml) |
| Android job | Android e2e acceptance (emulator) — **success** |
| iOS job | iOS e2e acceptance (simulator) — **success** |
| Android proof phases | 12 of 12 passed |
| iOS tests | 2 executed, 0 failures |
| Runtime/db/cache assertion | `RECONCILE VERIFICATION PASSED: exactly-once, fingerprints matched, no duplicates` |
| Screenshots | 23 Android + 18 iOS = 41 |

## Original artifacts (downloaded, never modified)

| file | bytes | sha256 |
|---|---:|---|
| `original-artifacts/android-acceptance.zip` | 53278965 | `ebbb8bcb972958f6a8ba481f9594f2f2e82db40070a38cb9ea6e82b006a8f151` |
| `original-artifacts/ios-acceptance.zip` | 38464769 | `e2d774711f36d1b2f6fea38319b15796d0bf7206a82b47ae4711ace3d16bd4d4` |

## Screenshots, as recorded by the run itself

Each row's sha256 comes from `SCREENSHOTS.manifest.json`, which the job generated
inside the run; all 41 were re-verified against the bytes after extraction (0
mismatches), and against the copy served at the PR image URL (0 mismatches).

| hosted as | platform | bytes | sha256 | path inside artifact |
|---|---|---:|---|---|
| `android-01-online-bootstrap.png` | android | 15888 | `53da98461fa8b3da49effda550118a42c3f18e7e7c9ea3952a8483464ece5420` | `screenshots/01-online-bootstrap.png` |
| `android-02-offline-list.png` | android | 17214 | `5b23bd09163a13782e8106b07d32bbbbe91bd0a8d597e1c54c1fead5fb82116b` | `screenshots/02-offline-list.png` |
| `android-03-offline-detail-stale.png` | android | 37686 | `20785dee62c4a0860cf2947ffb5a4f04fa51273c7f923e21d901d5a98c20d763` | `screenshots/03-offline-detail-stale.png` |
| `android-04-offline-cached-restart.png` | android | 25496 | `5a045f5dbd6591a73d675715eb6eec9bfa9935b5147d01e9f35b2eb6d2e60d42` | `screenshots/04-offline-cached-restart.png` |
| `android-05-reconnect-success.png` | android | 37950 | `d95e617ccfe019bdb81ddc8279e70c7322ca3f3accd4389cc2265b1c0a0d9e01` | `screenshots/05-reconnect-success.png` |
| `android-06-pending-edits-and-trades.png` | android | 37674 | `0ede87c94c84392bdad6eebb03c9382690bb3eb3fe0462ada6f967b64580291e` | `screenshots/06-pending-edits-and-trades.png` |
| `android-07-rollback-message.png` | android | 33641 | `9ab8820bcaaca86b12c847058381e371c6ae47bed2ae1772a329503ab7ca819b` | `screenshots/07-rollback-message.png` |
| `android-12-active-notification.png` | android | 40650 | `c9742a9ad7467881bd971b555eab0551f935a1bf7823566ce0a98bf8cc4b7ba4` | `screenshots/12-active-notification.png` |
| `android-i1-01-conflict-card.png` | android | 51747 | `c85ca640eb53d81fb76d372579dcf30800a2eac23fa1d4cf81bd4c3127d2d5dc` | `screenshots/i1-01-conflict-card.png` |
| `android-i1-02-after-use-server.png` | android | 45683 | `f0d764fd235bb18f9534dda886807d903317066d6cd76a891dcee5bdca52d4e6` | `screenshots/i1-02-after-use-server.png` |
| `android-i1-03-keep-mine-still-pending.png` | android | 53743 | `2ee156ebf7e7f18a6615c9115a24f6a3d4323e5abfff4a2a96a06308a5e9bda0` | `screenshots/i1-03-keep-mine-still-pending.png` |
| `android-i1-04-keep-mine-final.png` | android | 43782 | `408418a225ad27dae7b07308f3d1d114d5e2572af5e879431dd5e4848a71aa02` | `screenshots/i1-04-keep-mine-final.png` |
| `android-i2-01-offline-rename-skewed-clock.png` | android | 47319 | `657e41ea4377c58ef7a5b625e57a4743a2ebdb2ea84113cfd01aa06337313664` | `screenshots/i2-01-offline-rename-skewed-clock.png` |
| `android-i2-02-conflict-with-skewed-clock.png` | android | 51078 | `477eef76ec3962be63de5b6e054412c6f63c3a96098255fe851b530e7e36120c` | `screenshots/i2-02-conflict-with-skewed-clock.png` |
| `android-i3-01-optimistic-value-before-sync.png` | android | 39972 | `2360d5e8f4871bc732c11c9aaba83b9b893e2a70f3613bf8e958f336f89e64c6` | `screenshots/i3-01-optimistic-value-before-sync.png` |
| `android-i3-02-permanent-rejection-notification.png` | android | 42586 | `0d3e1c9af05bde09dc0de29336657edbf1cf1778c865a0f488441a244aa81127` | `screenshots/i3-02-permanent-rejection-notification.png` |
| `android-i3-03-original-value-restored.png` | android | 47473 | `20bad0f68fc0c0e036cdfe5980ddcec1b1d4cb68dbfe3ae8fa0f770eb0e086a3` | `screenshots/i3-03-original-value-restored.png` |
| `android-i4-01-data-quality-warnings.png` | android | 51799 | `13a02dc984fb1ead891d12b3ec83fb57097021fb9d54c6fa12e674102f3ecd56` | `screenshots/i4-01-data-quality-warnings.png` |
| `android-i5-01-approximate-alert-offline.png` | android | 35195 | `6977f78521aaeb3b94c2f26ada9ed27ab54505cc04418ba3168f659ad99eb115` | `screenshots/i5-01-approximate-alert-offline.png` |
| `android-i5-02-confirmed-after-reconnect.png` | android | 53355 | `f503042c1b38d8c49382c1673643299317f30204c8f84fe5e3b4003cf4cac34a` | `screenshots/i5-02-confirmed-after-reconnect.png` |
| `android-i5-03-corrected-after-reconnect.png` | android | 58428 | `0d9fc2d6dae118e08b84860990167b1585c0b020fa66a7828c9b6f1c41a8cfe1` | `screenshots/i5-03-corrected-after-reconnect.png` |
| `android-i6-01-alerts-screen-online.png` | android | 58471 | `5378a225dd3f91fff6a1073cee460f65fea684c360bcfe70761e787997e4557b` | `screenshots/i6-01-alerts-screen-online.png` |
| `android-i6-02-percentage-change-fired-offline.png` | android | 24968 | `843bad8198f46f10a542c7885dcf170ae9a6550c91a4844cfb6aa074ed275b77` | `screenshots/i6-02-percentage-change-fired-offline.png` |
| `ios-01-online-authenticated.png` | ios | 3015477 | `034841d8ebf52710c8321af3aa4371a1c69885c2693fd12c6b8348d74e4cdf3d` | `01-online-authenticated.png` |
| `ios-02-offline-list.png` | ios | 107542 | `a31e709da546a4f7f72d2fa09be74ec438e45f5da574924ae81ec59551f8623c` | `02-offline-list.png` |
| `ios-03-offline-detail-stale.png` | ios | 224900 | `f04e064f9f55d426f40e5c7c3f23a537d2d2fc1418befa82679cdc93c3bfbe69` | `03-offline-detail-stale.png` |
| `ios-04-offline-cached.png` | ios | 224900 | `f04e064f9f55d426f40e5c7c3f23a537d2d2fc1418befa82679cdc93c3bfbe69` | `04-offline-cached.png` |
| `ios-05-reconnect-success.png` | ios | 107190 | `cdf73bc9be9c11a1452c1bee98887a6e614693b9b06f4d193c4f2b61e1ba7170` | `05-reconnect-success.png` |
| `ios-06-pending-scalar-edit.png` | ios | 227373 | `8cd7f58a68d00cc9e12a39d06b7d9cfec4b78bf9826e00eee6912e5fae870a62` | `06-pending-scalar-edit.png` |
| `ios-i0-00-landing-after-launch.png` | ios | 55935 | `f38579f39aa2ceadbde8ddf39490bb540db86f732a39bff630a4b0194e4f6ded` | `ios-i0-00-landing-after-launch.png` |
| `ios-i0-01-after-sync.png` | ios | 107190 | `cdf73bc9be9c11a1452c1bee98887a6e614693b9b06f4d193c4f2b61e1ba7170` | `ios-i0-01-after-sync.png` |
| `ios-i1-01-offline-local-edit.png` | ios | 230760 | `37da1f1ff456ece4c4f39928fd53c1320926f1138592edd8b54f6c48c96af414` | `ios-i1-01-offline-local-edit.png` |
| `ios-i1-02-conflict-card.png` | ios | 243826 | `fa816f244a46042b2e383ebd3e3c365ae31012af501a1d0c410d4ad7b2a95b11` | `ios-i1-02-conflict-card.png` |
| `ios-i1-03-after-use-server.png` | ios | 227728 | `8acbdd3dbb18137954256887d10b6cc443795ef817d0f05a21e10c160b05b77a` | `ios-i1-03-after-use-server.png` |
| `ios-i1-04-second-conflict.png` | ios | 246738 | `076699c02a5e3c5aad7531f9aff339f7df5b2306b1aa7a4efb54abcea1a457e2` | `ios-i1-04-second-conflict.png` |
| `ios-i1-05-keep-mine-still-pending.png` | ios | 247830 | `638ea1b182646311ded0cfc48782ff9f1978d46c8bceb51bbe5f1423fdc3a5a3` | `ios-i1-05-keep-mine-still-pending.png` |
| `ios-i1-06-keep-mine-final.png` | ios | 226050 | `2299126f26a64a82445f3dcb1b5357c5e4d322b447c990525301d2b0c08a36b1` | `ios-i1-06-keep-mine-final.png` |
| `ios-i3-01-optimistic-value-before-sync.png` | ios | 212209 | `db1688ff4be0c0dedeb7714e218830dc172a6181b51b17d7a78654c040b6304b` | `ios-i3-01-optimistic-value-before-sync.png` |
| `ios-i3-02-rejection-notification.png` | ios | 348894 | `60dfb8dbaaa362d6682c9d3d1472c29582c8068300cb74fa44b96a87971d1997` | `ios-i3-02-rejection-notification.png` |
| `ios-i3-03-original-value-restored.png` | ios | 449385 | `4c3678b52c3ac491805480b04772c1ca1917bab49982ba97bace4ba4b0b3bcf5` | `ios-i3-03-original-value-restored.png` |
| `ios-i4-01-data-quality-warnings.png` | ios | 226632 | `f6f0cd0ff78de90821a09bf554bfb6866330a1537ef84b3c2bbfffa501783bf0` | `ios-i4-01-data-quality-warnings.png` |

## The six reviewer issues

| issue | PR comment | screenshots |
|---|---|---|
| 1 | [#issuecomment-5150895544](https://github.com/toloka-partners/a-vc-stock-visor/pull/2376#issuecomment-5150895544) | `android-i1-01-conflict-card.png`, `android-i1-02-after-use-server.png`, `android-i1-03-keep-mine-still-pending.png`, `android-i1-04-keep-mine-final.png`, `ios-i1-01-offline-local-edit.png`, `ios-i1-02-conflict-card.png`, `ios-i1-03-after-use-server.png`, `ios-i1-04-second-conflict.png`, `ios-i1-05-keep-mine-still-pending.png`, `ios-i1-06-keep-mine-final.png` |
| 2 | [#issuecomment-5150895585](https://github.com/toloka-partners/a-vc-stock-visor/pull/2376#issuecomment-5150895585) | `android-i2-01-offline-rename-skewed-clock.png`, `android-i2-02-conflict-with-skewed-clock.png` |
| 3 | [#issuecomment-5150895625](https://github.com/toloka-partners/a-vc-stock-visor/pull/2376#issuecomment-5150895625) | `android-i3-01-optimistic-value-before-sync.png`, `android-i3-02-permanent-rejection-notification.png`, `android-i3-03-original-value-restored.png`, `ios-i3-01-optimistic-value-before-sync.png`, `ios-i3-02-rejection-notification.png`, `ios-i3-03-original-value-restored.png` |
| 4 | [#issuecomment-5150895662](https://github.com/toloka-partners/a-vc-stock-visor/pull/2376#issuecomment-5150895662) | `android-i4-01-data-quality-warnings.png`, `ios-i4-01-data-quality-warnings.png` |
| 5 | [#issuecomment-5150895709](https://github.com/toloka-partners/a-vc-stock-visor/pull/2376#issuecomment-5150895709) | `android-i5-01-approximate-alert-offline.png`, `android-i5-02-confirmed-after-reconnect.png`, `android-i5-03-corrected-after-reconnect.png` |
| 6 | [#issuecomment-5150895754](https://github.com/toloka-partners/a-vc-stock-visor/pull/2376#issuecomment-5150895754) | `android-i6-01-alerts-screen-online.png`, `android-i6-02-percentage-change-fired-offline.png` |
