# GitDocs

The goal of this project is to provide a build process that aggregates READMEs and Wikis across all repos in an organization in GitHub, and converts it into a single, searchable static website, in relative real-time.

Specific Goals:

- [ ] Aggregates all readmes across all repos in an org
- [ ] Aggregates all wikis across all repos in an org
- [ ] Outputs a valid hugo static site project
- [ ] Listens for updates to readmes or wikis to trigger a new build
- [ ] Final build artifact is a docker image
- [ ] Ideally can provide javascript-based search across >1000 repos