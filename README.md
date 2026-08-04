# Subversion (svn)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Apache Subversion (SVN) is a centralized version control system that tracks changes to files and directories over time. It supports atomic commits, directory versioning, cheap branching and tagging, merge tracking, and binary file handling. SVN is served over HTTP/HTTPS using the WebDAV/DeltaV protocol via mod_dav_svn, or over a custom protocol using svnserve.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/svn/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/svn/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Apache
- Open Source
- Repository
- Source Control
- Svn
- Version Control
- Webdav

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### SVN WebDAV HTTP API

Apache Subversion exposes repository operations over HTTP/HTTPS using the WebDAV/DeltaV protocol via the mod_dav_svn Apache module. Clients use OPTIONS, PROPFIND, GET, PUT, REPORT, MKACTIVITY, CHECKOUT, MERGE, COPY, DELETE, and PROPPATCH to perform version control operations including checkout, commit, update, log retrieval, and branching.

- **Human URL:** [https://subversion.apache.org/docs/](https://subversion.apache.org/docs/)
- **Base URL:** `https://svn.example.com/repos/`

#### Tags

- Deltav
- Repository
- Version Control
- Webdav

#### Properties

- [Documentation](https://subversion.apache.org/docs/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/svn/refs/heads/main/openapi/svn-webdav-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Book](https://svnbook.red-bean.com/)
- [Protocol](https://svn.apache.org/repos/asf/subversion/trunk/notes/http-and-webdav/webdav-usage.html)
- [Postman Collection](collections/svn-webdav.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/svn-webdav.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SVN C Library API

The Subversion C library provides the low-level API for building tools and integrations. It includes the libsvn_client, libsvn_ra, libsvn_wc, and libsvn_repos libraries for client operations, repository access, working copy management, and server-side repository access respectively.

- **Human URL:** [https://subversion.apache.org/docs/api/latest/](https://subversion.apache.org/docs/api/latest/)

#### Tags

- C Library
- Integration
- Library

#### Properties

- [Documentation](https://subversion.apache.org/docs/api/latest/)
- [GitHub Repository](https://github.com/apache/subversion)
- [Postman Collection](collections/svn-webdav.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/svn-webdav.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SVN Python Bindings

Python bindings for Subversion C libraries, providing access to client and repository operations via pysvn and the official svn.client Python module.

- **Human URL:** [https://pysvn.sourceforge.io/](https://pysvn.sourceforge.io/)

#### Tags

- Python
- SDK

#### Properties

- [Documentation](https://pysvn.sourceforge.io/Docs/pysvn_prog_guide.html)
- [Postman Collection](collections/svn-webdav.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/svn-webdav.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SVNKit Java Library

SVNKit is a pure Java Subversion client library providing full access to Subversion repository and working copy data. Used by major IDE plugins including IntelliJ IDEA and Eclipse Subclipse.

- **Human URL:** [https://svnkit.com/](https://svnkit.com/)

#### Tags

- Java
- SDK

#### Properties

- [Documentation](https://svnkit.com/index.html)
- [Postman Collection](collections/svn-webdav.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/svn-webdav.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Getting Started](https://subversion.apache.org/quick-start)
- [Book](https://svnbook.red-bean.com/)
- [Downloads](https://subversion.apache.org/download/)
- [Security](https://subversion.apache.org/security/)
- [F A Q](https://subversion.apache.org/faq.html)
- [Community](https://subversion.apache.org/mailing-lists.html)
- [Git Hub](https://github.com/apache/subversion)
- [License](https://www.apache.org/licenses/LICENSE-2.0)
- [Features](https://subversion.apache.org/features.html)
- [Package](https://packages.apache.org/subversion)

## Maintainers

**Email:** dev@subversion.apache.org
**URL:** https://www.apache.org/
