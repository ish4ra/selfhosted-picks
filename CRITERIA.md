# Recommendation criteria

A project does not make this list just because it can be self-hosted.

## Strong signals

Prefer projects that are:

- actively maintained;
- open source with a clear license;
- useful beyond the initial setup experiment;
- documented well enough for normal users to operate;
- realistic on home-server hardware;
- easy to back up or restore;
- meaningfully better when self-hosted (privacy, ownership, cost, control, integrations or reliability).

## Reasons to exclude or add a warning

- effectively abandoned upstream;
- unclear licensing;
- requires an unnecessarily large stack for a tiny benefit;
- weak backup/restore story;
- insecure default deployment guidance;
- project is very new and not yet mature enough to trust with important data;
- duplicates another recommendation without a meaningful advantage.

## Difficulty labels

- **Easy** — one container/package and minimal configuration.
- **Medium** — several services, storage/permissions, reverse proxy or meaningful ongoing configuration.
- **Advanced** — requires deeper networking, identity, clustering, databases, storage design or careful operations.

## Resource labels

- **Light** — comfortable on small home servers/Raspberry Pi-class systems depending on workload.
- **Moderate** — benefits from a normal x86 mini PC/server and reasonable RAM.
- **Heavy** — media processing, photo ML, search indexing or other workloads that can consume significant CPU/GPU/RAM/storage.

## Philosophy

A short list of projects with clear trade-offs is more useful than a huge list of names.