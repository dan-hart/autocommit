# autocommit

Are you tired of having to come up with a commit message when you make such a trivial change, like a typo, and then having to type it in?

This little CLI script automatically generates a commit message based on the Git diff. It compares word-by-word and deduplicates identical changes.

### &rarr; [See commits committed by autocommit](https://github.com/search?q=committer%3Aautocommit-cli%5Bbot%5D&type=Commits)

## Installation

I haven't published this as a Gem yet, so you have to clone the repository and install by yourself. Ruby is needed.

```sh
git clone https://github.com/dtinth/autocommit.git
cd autocommit
chmod +x install.sh
sh install.sh
```

## Usage

```sh
$ autocommit         # Proposes a commit message, press Enter to commit.
$ autocommit -f      # Commits without proposing.
```
