# Codex guidance for OpenZ-Ballerman

- This is a fork of https://github.com/playopenz/OpenZ (upstream).
- Develop game changes on the `development` branch or on short-lived feature branches based on `development`.
- Keep `main` as the upstream integration branch. Do not commit game feature changes to `main`.
- Never force-push, reset away user changes, or resolve merge conflicts by blindly taking either side.
- Upstream synchronization is scheduled on `main`. Review and merge the proposed `main` -> `development` pull request before integrating updates.
- Before editing, inspect the Unity/C# project structure, applicable license, and existing tests. Keep changes focused and avoid altering imported assets or project settings unnecessarily.
- After changes, report files modified, tests run, and any Unity tests or manual checks that could not be completed.
- Do not merge pull requests or push to `main` unless the user explicitly requests it.
