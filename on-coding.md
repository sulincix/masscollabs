## On Coding Rules v1

### About Branches

1. devel-x(version number here)
2. master-x(version number here)
3. stable-x(version number here)
4. oldstable-x(version number here)
5. legacy-x(version number here)

```
devel is development branch. It is not stable yet.
master is main branch for users/communities.
stable is current stable branch.
oldstable is old version but supported.
legacy is old version and not supported.
```

### About Tags

Tag string should be like this:

1. v1.2.0 (classic versioning)
2. 2020.05 (year.month style)
3. 20200512 (yearmonthdate style)
4. 123 (single number versioning)


### About Pull Requests

Send your Pull Requests to devel-x branch first. Then "Masscollabs core team" will analyze the code/information that you have sent.

### About Merging Source Code

1. Next stage is we'll merge devel-x source code/information with master-x branch; this is a release stage.
2. Then the next stage is testing the source code/information and merging the source code/information with stable-x branch

## Preferred Github Account Settings for "core team"

### Your Account should have the following features when commiting

1. SSH key
2. GPG key
3. 2 Factor Authentication
4. Personal access token for one time commit passphrase

### For other contributers when commiting

You may send your Pull Request from Github web page, or from command line without GPG signed commit, 2 Factor Authentication and Personal access token 

## Account Privacy of members

You always have the right not to declare yourself as a public member; you can always be a private member.

#### Code distribution rules

Masscollabs never puts source code/information into master-x branches without security testing and correcting the information. Test twice your code and information and then send your pull request to all branches (devel-x , master-x and stable-x). Masscollabs plays, fixes, tries, makes.

This document is licensed under the terms of the [GNU Free Documentation License](https://www.gnu.org/licenses/fdl-1.3.en.html)

If you have any questions please create an issue on this repository or join the [Masscollabs Telegram group](https://t.me/masscollabs) to ask your question.

on-coding.md Coding Rules, Account Privacy and Contribution information for Masscollabs; this document will be updated by getting feedback from members and other contributors.


