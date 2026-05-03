# Subversion (SVN)

Apache Subversion (SVN) is a centralized version control system that tracks changes to files and directories over time. It supports atomic commits, directory versioning, cheap branching and tagging, merge tracking, and binary file handling. SVN repositories are served over HTTP/HTTPS using the WebDAV/DeltaV protocol via mod_dav_svn, or over a custom protocol using svnserve.

**URL:** [https://subversion.apache.org/](https://subversion.apache.org/)

## Tags

- Apache, Open Source, Repository, Source Control, Svn, Version Control, Webdav

## APIs

### SVN WebDAV HTTP API

Access and manage SVN repositories over HTTP/HTTPS via the WebDAV/DeltaV protocol served by mod_dav_svn.

**Human URL:** [https://subversion.apache.org/docs/](https://subversion.apache.org/docs/)

#### Tags

- Deltav, Repository, Version Control, Webdav

#### Properties

- [Documentation](https://subversion.apache.org/docs/)
- [OpenAPI](openapi/svn-webdav-openapi.yml)
- [Book](https://svnbook.red-bean.com/)
- [Protocol](https://svn.apache.org/repos/asf/subversion/trunk/notes/http-and-webdav/webdav-usage.html)

### SVN C Library API

Low-level C API for building SVN tools and integrations.

**Human URL:** [https://subversion.apache.org/docs/api/latest/](https://subversion.apache.org/docs/api/latest/)

### SVNKit Java Library

Pure Java Subversion client library for IDE plugins and integrations.

**Human URL:** [https://svnkit.com/](https://svnkit.com/)

## Artifacts

### OpenAPI

| File | Description |
|---|---|
| [openapi/svn-webdav-openapi.yml](openapi/svn-webdav-openapi.yml) | SVN WebDAV HTTP API — repository operations over HTTP/HTTPS |

### Rules

| File | Description |
|---|---|
| [rules/svn-rules.yml](rules/svn-rules.yml) | Spectral ruleset for SVN WebDAV API conventions |

### Capabilities

| File | Description |
|---|---|
| [capabilities/version-control.yaml](capabilities/version-control.yaml) | Unified SVN version control workflow capability |
| [capabilities/shared/svn-webdav.yaml](capabilities/shared/svn-webdav.yaml) | Shared SVN WebDAV API definitions |

### JSON Schema

| File | Description |
|---|---|
| [json-schema/svn-repository-schema.json](json-schema/svn-repository-schema.json) | JSON Schema for SVN Repository |
| [json-schema/svn-commit-schema.json](json-schema/svn-commit-schema.json) | JSON Schema for SVN Commit |

### JSON Structure

| File | Description |
|---|---|
| [json-structure/svn-repository-structure.json](json-structure/svn-repository-structure.json) | SVN repository structural documentation |

### JSON-LD

| File | Description |
|---|---|
| [json-ld/svn-context.jsonld](json-ld/svn-context.jsonld) | JSON-LD context for SVN version control concepts |

### Examples

| File | Description |
|---|---|
| [examples/svn-get-file-example.json](examples/svn-get-file-example.json) | Example: Get file at HEAD revision |
| [examples/svn-commit-example.json](examples/svn-commit-example.json) | Example: Full commit transaction lifecycle |

### Vocabulary

| File | Description |
|---|---|
| [vocabulary/svn-vocabulary.yml](vocabulary/svn-vocabulary.yml) | Apache Subversion domain vocabulary |

## Common Properties

- [Getting Started](https://subversion.apache.org/quick-start)
- [Book](https://svnbook.red-bean.com/)
- [Downloads](https://subversion.apache.org/download/)
- [Security](https://subversion.apache.org/security/)
- [FAQ](https://subversion.apache.org/faq.html)
- [Community](https://subversion.apache.org/mailing-lists.html)
- [GitHub](https://github.com/apache/subversion)
- [License](https://www.apache.org/licenses/LICENSE-2.0)

## Maintainers

**Name:** Apache Software Foundation
**Email:** dev@subversion.apache.org

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-02
