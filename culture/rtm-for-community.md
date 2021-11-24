# Response Time Maximum for Community

English | [简体中文](./rtm-for-community_CN.md)

The concept of RTM (Response Time Maximum) for community, is inspired by [Chef OSS Best Practice](https://github.com/chef/chef-oss-practices) of [repo states](https://github.com/chef/chef-oss-practices/blob/main/repo-management/repo-states.md).

We extend it and define 5 states for our repository.

- Active
- Refactoring
- Maintained
- Prototyping
- Deprecated

## Active

Repositories in **active** state are under active development. The RTM of active repo is 7 days.

## Refactoring

Repositories in **refactoring** state are under active development where bugs will be fixed, but new feature work is locked until the refactoring completed. All the factoring repositories will provider an expected completed time on roadmap. The RTM of refactoring repo is 7 days ~ 30 days.

## Maintained

Repositories in **maintained** state are maintained where bugs will be fixed, but no new feature work should be expected. The RTM of maintained repo is 1 Month.

## Prototyping

Repositories in a **prototyping** state should be considered alpha or beta. New feature requests and bug fixes should not be expected until the project moves to the **active** state. There is no expected RTM for prototyping repository.

## Deprecated

Repositories in a **deprecated** state are no longer maintained. No new features or bug fixes should be expected. There is no expected RTM for deprecated repository.
