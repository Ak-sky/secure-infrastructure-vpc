# secure-infrastructure-vpc

Documentation repository for deployment guide docs for "VPC landing zone deployable architectures" ([staging output](https://test.cloud.ibm.com/docs/secure-infrastructure-vpc))

## Creating content

### Drafting content

1.  Clone this repo if you have write privileges. Otherwise, fork the repo.
1.  Create a working branch from the `draft` branch.
1.  Make your changes to the Markdown content.

    We use Markdown with a few custom extensions to source the docs. For tips about how to structure and style your docs with IBM Cloud Markdown, see [Quick tips for authoring in IBM Cloud Docs](https://test.cloud.ibm.com/docs/writing?topic=writing-solution-guides#solution-guides-include-quick-tips) in "Creating solution, deployment, and migration guides".
1.  Commit your updates.
1.  Create a pull request from your branch to `draft`.

When changes are merged to the `draft` branch, they are built and published to staging at https://test.cloud.ibm.com/docs-draft/secure-infrastructure-vpc.

### Promoting to the review branch

The internal `review` branch is meant for "pre-production" content. We use the branch to review, validate, and finalize content. When you're ready for your changes to be reviewed, create a PR from `draft` to `review`.

When changes are merged to the `review` branch, they are built and published to staging at https://test.cloud.ibm.com/docs/secure-infrastructure-vpc.

### Publishing to production

1.  Work in `draft` and `review` branches until you're happy with the output on staging.
1.  Merge or copy content from `draft` to `publish`. For more information about how to merge from draft to production, see https://test.cloud.ibm.com/docs-internal/writing?topic=writing-doc-git-workflows#doc-build-merge.

    :exclamation: **Important:** Do not expose IBM Confidential information in your commits to `publish`. Commits made in the `publish` branch become public record. When you commit to the `publish` branch, the source is mirrored in a public GitHub repo at https://github.com/ibm-cloud-docs/secure-infrastructure-vpc so that customers can view and contribute to your source.
1.  Create a pull request.

When changes are merged to the `production` branch, they are built and published to production at https://cloud.ibm.com/docs/secure-infrastructure-vpc. Changes don't get promoted to the `publish` branch until they are reviewed, edited, and approved by a one of the doc maintainers.

## Monitoring

### Monitoring builds

The Slack channel [#docs-secure-infrastructure-vpc](https://ibm-cloudplatform.slack.com/archives/C04R61SEM98) displays information about builds.

### Monitoring content quality

You can monitor your content quality on the Content Quality Dashboard (CQD): https://cops.console.test.cloud.ibm.com/docs-quality-dashboard. The CQD for docs content is updated daily For more information, see https://test.cloud.ibm.com/docs-internal/writing?topic=writing-cqd.

## More information

- Learn about the suggested content for each type of solution docs at https://test.cloud.ibm.com/docs-internal/writing?topic=writing-writing-solution.
