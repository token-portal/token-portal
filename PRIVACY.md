# Privacy Statement

**Token Portal** (the "Plugin") is a Figma plugin that exports Figma variables and styles into
code formats and, at the user's request, commits the generated files to a Git repository. This
statement describes what data the Plugin processes and where that data is transmitted.

## Data the Plugin reads

The Plugin reads design data from the Figma file in which it is run: variables, text styles and
effect styles. Where a variable references a variable from an enabled library, the referenced
value is also read. Reading occurs when the Plugin is started and when it regains focus. Reading
does not involve any network transmission.

## Data transmission

Generated files are transmitted exclusively to the Git hosting service and repository configured
by the user (GitHub or GitLab), and only upon an explicit action: connecting a repository,
requesting a check, or publishing. The Plugin's network access is declared in its manifest and is
restricted to `api.github.com` and `gitlab.com`.

The Plugin operates without any first-party server infrastructure. It does not collect analytics,
telemetry, usage statistics or crash reports, and no background processes run between sessions.
When only the local export function (ZIP download) is used, no data leaves the user's machine.

## Access tokens

A repository access token provided by the user is stored locally through Figma's plugin storage,
and only when the corresponding option is enabled. Figma stores this value unencrypted; the
Plugin states this at the point of entry. Disconnecting a repository deletes the stored token.
Tokens are transmitted only to the Git hosting service they belong to and never appear in
generated files or error messages.

## Personal data

The Plugin does not collect, store or transmit personal data. The developer has no access to
users' design data, repositories, tokens or identities. Payment status, where applicable, is
determined and held solely by Figma.

## Contact

Enquiries regarding this statement may be submitted via the
[public issue tracker](https://github.com/token-portal/token-portal/issues). Any discrepancy
between this statement and the Plugin's actual behaviour is treated as a defect.
