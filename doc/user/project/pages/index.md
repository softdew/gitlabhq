# GitLab Pages

With GitLab Pages you can host your website at no cost.

Your files live in a GitLab project's [repository](../repository/index.md),
from which you can deploy [static websites](#explore-gitlab-pages).
GitLab Pages supports all static site generators (SSGs).

## Getting Started

Follow the steps below to get your website live. They shouldn't take more than
5 minutes to complete:

- 1. [Fork](../../../gitlab-basics/fork-project.md#how-to-fork-a-project) an [example project](https://gitlab.com/pages)
- 2. Change a file to trigger a GitLab CI/CD pipeline
- 3. Visit your project's **Settings > Pages** to see your **website link**, and click on it. Bam! Your website is live.

_Further steps (optional):_

- 4. Remove the [fork relationship](getting_started_part_two.md#fork-a-project-to-get-started-from) (_You don't need the relationship unless you intent to contribute back to the example project you forked from_).
- 5. Make it a [user/group website](getting_started_part_one.md#user-and-group-websites)

**Watch a video with the steps above: https://www.youtube.com/watch?v=TWqh9MtT4Bg**

_Advanced options:_

- [Use a custom domain](getting_started_part_three.md#adding-your-custom-domain-to-gitlab-pages)
- Apply [SSL/TLS certification](getting_started_part_three.md#ssl-tls-certificates) to your custom domain

## Explore GitLab Pages

With GitLab Pages you can create [static websites](getting_started_part_one.md#what-you-need-to-know-before-getting-started)
for your GitLab projects, groups, or user accounts. You can use any static
website generator: Jekyll, Middleman, Hexo, Hugo, Pelican, you name it!
Connect as many custom domains as you like and bring your own TLS certificate
to secure them.

Read the following tutorials to know more about:

- [Static websites and GitLab Pages domains](getting_started_part_one.md)
- [Forking projects and creating new ones from scratch, URLs and baseurls](getting_started_part_two.md)
- [Custom domains and subdomains, DNS records, SSL/TLS certificates](getting_started_part_three.md)
- [How to create your own `.gitlab-ci.yml` for your site](getting_started_part_four.md)
- [Technical aspects, custom 404 pages, limitations](introduction.md)
- [Hosting on GitLab.com with GitLab Pages](https://about.gitlab.com/2016/04/07/gitlab-pages-setup/) (outdated)

_Blog posts series about Static Site Generators (SSGs):_

- [SSGs part 1: Static vs dynamic websites](https://about.gitlab.com/2016/06/03/ssg-overview-gitlab-pages-part-1-dynamic-x-static/)
- [SSGs part 2: Modern static site generators](https://about.gitlab.com/2016/06/10/ssg-overview-gitlab-pages-part-2/)
- [SSGs part 3: Build any SSG site with GitLab Pages](https://about.gitlab.com/2016/06/17/ssg-overview-gitlab-pages-part-3-examples-ci/)

_Blog posts for securing GitLab Pages custom domains with SSL/TLS certificates:_

- [CloudFlare](https://about.gitlab.com/2017/02/07/setting-up-gitlab-pages-with-cloudflare-certificates/)
- [Let's Encrypt](https://about.gitlab.com/2016/04/11/tutorial-securing-your-gitlab-pages-with-tls-and-letsencrypt/) (outdated)
- [StartSSL](https://about.gitlab.com/2016/06/24/secure-gitlab-pages-with-startssl/) (deprecated)

## Advanced use

- [Posting to your GitLab Pages blog from iOS](https://about.gitlab.com/2016/08/19/posting-to-your-gitlab-pages-blog-from-ios/)
- [GitLab CI: Run jobs sequentially, in parallel, or build a custom pipeline](https://about.gitlab.com/2016/07/29/the-basics-of-gitlab-ci/)
- [GitLab CI: Deployment & environments](https://about.gitlab.com/2016/08/26/ci-deployment-and-environments/)
- [Building a new GitLab docs site with Nanoc, GitLab CI, and GitLab Pages](https://about.gitlab.com/2016/12/07/building-a-new-gitlab-docs-site-with-nanoc-gitlab-ci-and-gitlab-pages/)
- [Publish code coverage reports with GitLab Pages](https://about.gitlab.com/2016/11/03/publish-code-coverage-report-with-gitlab-pages/)

## Admin GitLab Pages for CE and EE

Enable and configure GitLab Pages on your own instance (GitLab Community Edition and Enterprise Editions) with
the [admin guide](../../../administration/pages/index.md).

**Watch the video: https://www.youtube.com/watch?v=dD8c7WNcc6s**

## More information about GitLab Pages

- For an overview, visit the [feature webpage](https://about.gitlab.com/features/pages/)
- Announcement (2016-12-24): ["We're bringing GitLab Pages to CE"](https://about.gitlab.com/2016/12/24/were-bringing-gitlab-pages-to-community-edition/)
- Announcement (2017-03-06): ["We are changing the IP of GitLab Pages on GitLab.com"](https://about.gitlab.com/2017/03/06/we-are-changing-the-ip-of-gitlab-pages-on-gitlab-com/)
