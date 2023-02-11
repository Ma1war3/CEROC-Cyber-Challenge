# Welcome to Nibble

This is the Proof-Of-Concept repository for the TN Tech CEROC Center Cyber Challenge.  This project is written in python and utilizes the [discord.py](https://discordpy.readthedocs.io/en/stable/) library as its discord API framework.  This is subject to change, and future change.

Any major changes in functionality shall either be provided in the
form of a changelog or appended section to this README.

## What is this for?

This bot is a managerial and activity bot that seeks to
provide access to and management of Cyber Challenges, which 
seek to improve programmer's abilities in cybersecurity.

## How do I help?

To contribute, create a fork of the project and clone it locally.
Then, run the following commands:

```bash
virtualenv .env \
  && source .env/bin/activate \
  && pip install -r requirements.txt
```

You will need to have both `virtualenv`, `python3`, and `pip`
installed in order to set up this project for development.
After your dependencies are set up and ready to go, you can
begin to make your local edits and commits.

Ensure that your commit does not introduce foreign files
that have not already been authorized to be introduced
into the repo.  The provided `.gitignore` is there to
help assist in that endeavor.In general, most PRs 
should leave the actual file structure as it is currently.

## Style Guidelines

This project uses three major style guides when it comes to 
development on this project:

### Commit Guidelines

This project uses the NIST Commit Styleguide, [which can be
found here](https://pages.nist.gov/dioptra/dev-guide/contributing-commit-styleguide.html).
The purpose of using a style guide for commits is to ensure
the overall quality and consistency of edits is maintained
across all maintainers and environments.

### Code Guidelines

This project uses the Python PEP8 Styleguide, [which can be
found here](https://peps.python.org/pep-0008/).  These guidelines are highly opinionated
and will ensure the most consistent and well-formed code
across all environments.  PyCharm Professional Edition
utilizes a PEP8 linter that should ensure code written 
remains compliant.

### Doc String Guidelines

This project uses the Python PEP257 Doc String Conventions
guide, [which can be found here](https://peps.python.org/pep-0257/).
This helps to ensure consistent documentation throughout
the code base, which is often a large code debt when left
unchecked.