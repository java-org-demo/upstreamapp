# Upstream Application

This app is to demonstrate an app at the top of a dependency tree within a
company.  The other applications are downstream of this one (depend/subscribe
to artifacts from this app).  Which means this one must be built first, and
when a new version is released, any downstream applications should be updated
to point at the new version.