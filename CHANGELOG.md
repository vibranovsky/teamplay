# v0.4.0 (Sun Sep 08 2024)

#### 🚀 Enhancement

- `@teamplay/backend`, `teamplay`
  - feat: use patched sharedb-mingo-memory which fully supports $aggregate with $lookup ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.3.6 (Fri Sep 06 2024)

#### 🐛 Bug Fix

- `@teamplay/server-aggregate`
  - fix(server-aggregate): fix checking whether the query is the named aggregation ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.4.0 (Fri Sep 06 2024)

#### 🚀 Enhancement

- `@teamplay/backend`, `@teamplay/server-aggregate`, `teamplay`
  - feat: allow running aggregations on server side [#6](https://github.com/startupjs/teamplay/pull/6) ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.3.4 (Thu Sep 05 2024)

#### 🐛 Bug Fix

- `teamplay`
  - fix(teamplay): fix .getId() for doc signals in aggregation results ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.3.2 (Tue Sep 03 2024)

#### 🐛 Bug Fix

- `@teamplay/backend`, `teamplay`, `@teamplay/utils`
  - fix: fix aggregations support. Add unit tests for them [#5](https://github.com/startupjs/teamplay/pull/5) ([@cray0000](https://github.com/cray0000))

#### ⚠️ Pushed to `master`

- `@teamplay/backend`, `teamplay`, `@teamplay/utils`
  - Merge branch 'master' of github.com:startupjs/teamplay ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.3.2 (Tue Sep 03 2024)



---

# v0.4.0 (Fri Aug 30 2024)

#### 🚀 Enhancement

- `@teamplay/sharedb-access`, `teamplay`
  - feat(access): add userId to the permission denied log ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.2.7 (Fri Aug 30 2024)

#### 🐛 Bug Fix

- `teamplay`
  - fix: implement a classical useSub() and move update logic into observer component [#4](https://github.com/startupjs/teamplay/pull/4) ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.2.6 (Tue Aug 27 2024)

#### 🐛 Bug Fix

- `@teamplay/schema`
  - feat(@teamplay/schema): add 'ajv-errors' for custom error message [#3](https://github.com/startupjs/teamplay/pull/3) ([@pvturchik](https://github.com/pvturchik))

#### Authors: 1

- Pavel Turchik ([@pvturchik](https://github.com/pvturchik))

---

# v0.2.5 (Mon Aug 26 2024)

#### 🐛 Bug Fix

- `@teamplay/backend`, `@teamplay/sharedb-access`, `@teamplay/utils`
  - fix(backend): fix accessControl, allow to pass a customValidator option for it ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.3.0 (Mon Aug 26 2024)

#### 🚀 Enhancement

- `@teamplay/backend`, `@teamplay/sharedb-access`, `teamplay`, `@teamplay/utils`
  - feat: add access control [#2](https://github.com/startupjs/teamplay/pull/2) ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.2.3 (Tue Aug 13 2024)

#### 🐛 Bug Fix

- `teamplay`
  - fix(teamplay): don't try to call the destructor twice (might happen in strict mode, on background render, etc.) ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.2.2 (Thu Aug 08 2024)

#### 🐛 Bug Fix

- `teamplay`
  - fix(teamplay): optimize setDiffDeep -- return the original object if the reference to be updated is the same object (don't try to perform a deep comparison) ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.2.1 (Tue Aug 06 2024)

#### 🐛 Bug Fix

- `teamplay`
  - fix(teamplay): don't try to deep update non-plaid objects when doing setDiffDeep on local data ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.2.0 (Tue Aug 06 2024)

#### 🚀 Enhancement

- `teamplay`
  - feat: implement aggregations; fix query rerender; [#1](https://github.com/startupjs/teamplay/pull/1) ([@cray0000](https://github.com/cray0000))

#### ⚠️ Pushed to `master`

- docs: add more API docs ([@cray0000](https://github.com/cray0000))
- Update README.md ([@cray0000](https://github.com/cray0000))
- `@teamplay/channel`
  - Update README.md ([@cray0000](https://github.com/cray0000))
- `teamplay`
  - Update README.md ([@cray0000](https://github.com/cray0000))
  - docs: fix createdAt in examples -- has to be unixtime ([@cray0000](https://github.com/cray0000))
  - docs: add docs using rspress and deploy them to Github Pages ([@cray0000](https://github.com/cray0000))
  - readme: document react integration and awaiting setters ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.2.0 (Wed Jul 03 2024)

#### 🚀 Enhancement

- `teamplay`
  - feat: expose an explicit 'useSub()' function to be used inside React components instead of sub() ([@cray0000](https://github.com/cray0000))

#### ⚠️ Pushed to `master`

- minor(example): fix css unit ([@cray0000](https://github.com/cray0000))
- `teamplay`
  - readme: add Usage section with introduction and documentation ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.2.0 (Sat Jun 29 2024)

#### 🚀 Enhancement

- `@teamplay/channel`, `teamplay`
  - feat(channel): add 'authorize' option for server-side to authorize connection requests; add 'getConnectionUrl' option for client-side to modify the connection url ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.2.0 (Thu Jun 06 2024)

#### 🚀 Enhancement

- `teamplay`
  - feat(teamplay): support passing array to sub() for multiple parallel subscriptions ([@cray0000](https://github.com/cray0000))

#### 🐛 Bug Fix

- `teamplay`
  - fix(teamplay): correctly handle array indexes; add more array methods - reduce, find; return id from .add ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.1.13 (Wed Jun 05 2024)

#### 🐛 Bug Fix

- `teamplay`
  - fix(teamplay/react): update signal ref if it changes ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.1.12 (Wed Jun 05 2024)

#### 🐛 Bug Fix

- `@teamplay/cache`, `teamplay`
  - fix(teamplay): change observer() update logic to use useSyncExternalStore; hold reference to signals within react context to prevent GCing them while component is still alive; don't unsubscribe from docs which were indirectly fetched by a query ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.1.11 (Sun Jun 02 2024)

#### 🐛 Bug Fix

- `teamplay`
  - fix: allow only working with public collections on the server since there is no user-separation for private collections ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.2.0 (Sun Jun 02 2024)

#### 🚀 Enhancement

- `teamplay`
  - feat(teamplay/Signal): add simple implementations for .pop() and .push() ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.2.0 (Sat Jun 01 2024)

#### 🚀 Enhancement

- `teamplay`
  - feat(teamplay/Signal): add getId() method which returns the last segment ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.1.8 (Fri May 31 2024)

#### 🐛 Bug Fix

- `@teamplay/backend`, `teamplay`, `@teamplay/utils`
  - fix: move uuid into utils package ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.1.7 (Fri May 31 2024)

#### 🐛 Bug Fix

- `@teamplay/backend`, `teamplay`
  - fix: use older uuid version which does not depend on the crypto module (RN does not have it) ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.1.6 (Fri May 31 2024)

#### 🐛 Bug Fix

- `teamplay`
  - fix(teamplay): mock WeakRef and FinalizationRegistry to work in Expo ([@cray0000](https://github.com/cray0000))

#### ⚠️ Pushed to `master`

- `@teamplay/backend`, `@teamplay/cache`, `@teamplay/channel`, `@teamplay/debug`, `@teamplay/schema`, `@teamplay/server-aggregate`, `@teamplay/sharedb-access`, `@teamplay/sharedb-schema`, `teamplay`, `@teamplay/utils`
  - chore: add .npmignore to all packages with CHANGELOG.md ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# (Mon May 27 2024)

#### 🚀 Enhancement

- `@teamplay/backend`, `@teamplay/schema`, `@teamplay/server-aggregate`, `@teamplay/sharedb-access`, `@teamplay/sharedb-schema`, `teamplay`, `@teamplay/utils`
  - feat: move backend implementation from startupjs. Add an example app. ([@cray0000](https://github.com/cray0000))

#### ⚠️ Pushed to `master`

- chore: add name to example app ([@cray0000](https://github.com/cray0000))
- chore: add version to example app ([@cray0000](https://github.com/cray0000))
- chore: add explicit release commands to publish patch and minor since 'auto' doesn't take 0-based version into account ([@cray0000](https://github.com/cray0000))
- `teamplay`
  - readme: add example readme ([@cray0000](https://github.com/cray0000))
  - chore(example): add live reload support whenever client.js changes ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.1.4 (Thu May 23 2024)

#### 🐛 Bug Fix

- `@teamplay/channel`, `teamplay`
  - fix: rename old references to startupjs packages into teamplay packages ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.1.3 (Thu May 23 2024)

#### 🐛 Bug Fix

- `teamplay`
  - fix: add 'events' since sharedb client requires it to work correctly ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.1.2 (Thu May 23 2024)

#### 🐛 Bug Fix

- `@teamplay/cache`, `teamplay`
  - fix: re-export cache as 'teamplay/cache' ([@cray0000](https://github.com/cray0000))

#### ⚠️ Pushed to `master`

- chore: update 'release' script to do an actual release ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))

---

# v0.1.1 (Thu May 23 2024)

#### 🐛 Bug Fix

- `@teamplay/cache`, `@teamplay/channel`, `@teamplay/debug`, `teamplay`
  - fix: dummy. trigger version bump ([@cray0000](https://github.com/cray0000))

#### Authors: 1

- Pavel Zhukov ([@cray0000](https://github.com/cray0000))
