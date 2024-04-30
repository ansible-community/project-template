# Maintainer guide

Welcome to the PROJECTNAME Maintainer guide!

> We encourage you to promote outside contributors as maintainers based on their contribution to the project. However, if the policy does not allow outside maintainers, remove irrelevant sections. The communication and release-related sections should be present in any case.

> If your project is not going to have a docsite (in case it is very simple and having a docsite would be an overkill), the following information should be present in your project MAINTAINING.md file and referred to from the [README template](https://github.com/ansible-community/project-template/blob/main/README.md).

> In the following sections, if the content is as simple as a few lines, put it in there, otherwise create separate files and refer to them from the sections. Add other sections if needed.

## Communication

Have questions or want to share feedback? See the [Community guide](community_guide.md)!

## How to become a maintainer

A PROJECTNAME maintainer is a contributor trusted by the community who makes significant and regular contributions to the project and who has shown themselves as a specialist in the related area. The maintainers have extended permissions in the project repository.

A person interested in becoming a maintainer and satisfying the requirements may either self-nominate or be nominated by another maintainer. To nominate a candidate, create a GitHub issue in the relevant collection repository.

## Maintainer responsibilities

Project maintainers provide feedback, responses, or actions on pull requests or issues in a reasonably timely manner. They can also update the project contributor and maintainer guidelines, in collaboration with the PROJECTNAME community and the other maintainers of the project.

In general, project maintainers:

- Act in accordance with the [Community Code of Conduct](link-to-CoC-here).
- Track activities in the repository (click `Watch` > `All activity` in GitHub).
- Keep README, development guidelines, and other general project documentation relevant.
- Review and commit changes made by other contributors.
- Backport changes to supported branches.
- Address or assign issues to appropriate contributors.
- Release the project.
- Represent the project in the community and in inter-project communication.
- Build a healthy community to increase the number of active contributors and maintainers around collections.

Multiple maintainers can divide responsibilities among each other.

## Releasing

### Versioning and deprecation

> Describe the versioning policy the project follows (such as [SemVer](https://semver.org/)). If defined, explain how often major, minor, and patch versions are released. Describe how deprecations are done. Put links to the changelog and roadmaps if relevant.

### Conducting releases

> Describe how releases are planned, conducted, and announced. For easy onboarding, create a separate step-by-step releasing guide (see the [example](https://docs.ansible.com/ansible/devel/community/collection_contributors/collection_release_without_branches.html#collection-release-without-branches) for collections).

## Stepping down as a maintainer

If you feel you do not have time to maintain the project anymore, we ask that you do not step down silently. Please open an issue in the project repository announcing the decision.

If you are the only maintainer, try to find new maintainers from active contributors and promote them if they agree to take the responsibility for the project.

If you failed to find a replacement, create a pinned issue in the repository announcing that the project needs new maintainers. Also make the announcement on the forum under corresponding category/tags and in the [Bullhorn newsletter](https://forum.ansible.com/t/about-the-newsletter-category/166).
