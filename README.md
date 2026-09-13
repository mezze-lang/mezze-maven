# mezze-maven

The Mezze language's public maven repository. Consumed via
`https://raw.githubusercontent.com/mezze-lang/mezze-maven/main/` from a
Mezze project's `[[maven-repo]]` entry:

```toml
[[maven-repo]]
id  = "mezze-lang"
url = "https://raw.githubusercontent.com/mezze-lang/mezze-maven/main/"
```

Layout follows the standard maven repository convention. Every artifact
carries a `.pom`, a `.sha1`, and an `.md5`; `maven-metadata.xml` at each
artifact root lists the released versions.

## Currently hosted

- `land.meridia.mezze:polyglot-python-natives:0.2.0` — Python interop
  native handlers for the Mezze language.
