# Contributing

Thank you for being a part of the Perch team!

Here are some helpful tips for contributing to the project.

## Issues ( features, bugs, etc... )

If you'd like to request a feature / enhancement or report a bug / pain point, please use GitHub Issues.

There are templates for most issues types, and a blank issue for all other feedback.

Before opening an issue, PLEASE look for an existing issue, open or closed, and leave a comment there instead.

Once your issue is triaged, it will be tagged and commented on by the team.

## Pull requests

The development team reviews all code prior to merging with Pull Requests.

Here are some things you can do to expedite the review process:

- Use the template ( so people can review quickly )
- Tag related issues with `fixes #1234`, `closes #1234`, or `connects #1234` so Github stays up to date
- Include a screenshot or GIF if your work has a visual component ( so we know what it looks like )
- Include a sample request if your work has an API component ( so we know how to use it )
- Run the linters and automated tests before submitting ( so we don't fuss over styles )
- Use the WIP tag if you are not ready for someone to review your work ( so we don't waste effort )

## Coding Practices

### Python

The API for Perchweb is written in Python 3 atop Django 2.0 and other Python packages.

Here are some tips:

- Use Python 3 and PEP8

### Javascript

Perchweb has a UI component that is built on top of React and a bunch of other Javascript packages.

Here are some tips:

- Use the latest Node and NPM version ( sorry Yarn fans )
- Be sure to `npm install` and restart webpack when pulling a new branch
- Use eslint and Prettier plugins with your editor or run `npm run lint` before committing
- See this guide for [making great React code at Perch](https://docs.google.com/presentation/d/1EpxHevecAqPDRspvmJAUPwPHkASXDbWVvKpZztMp5ms/edit?usp=drive_web&ouid=106394523405700250728)
