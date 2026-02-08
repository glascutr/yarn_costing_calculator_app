# `lib/` — Developer / Agent Guide

Purpose: contains Flutter UI, widgets, and app wiring. Keep UI components focused on presentation; place business logic in services/providers.

How agents should modify:
- Add unit tests in `test/` for any logic added.
- Update `lib/README.md` and `CLAUDE.md` if you change module responsibilities.

Run & test:
- `flutter pub get`
- `flutter test`

Doc rules:
- Keep code comments minimal. If overriding behavior, document with: "Overrides `ParentClass.method()` — see `ParentClass.method()`".
