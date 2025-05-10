On pull request:

- Code Linters:
    - JS: ESLint ([I trust the redditors](https://www.reddit.com/r/node/comments/1ggr69o/what_are_the_best_linters_for_nodejs/))
    - CSS: Stylelint (11k stars on git probably good)
    - HTML: HTMLHint ([I trust the redditors again](https://www.reddit.com/r/webdev/comments/b23301/what_do_you_guys_use_for_html_linting/))
    We'll have these running locally.

- Code quality via tool:
    - Codeclimate (Because it was the first one up, I'll have to actually try using it to come to a decision)
    From my understanding, Codeclimate is basically a much tougher ESLint that 
    can easily be set up to do stuff in Github Actions.

- Run unit tests
    - Jest (We've seen it work in lab, test cases are easy to write, I like it)

- Generate documentation, generate webpage for PR viewers to see
    - JSDocs (I guess?)

We should also be able to run any of these locally whenever we want, so that we don't 
have to spam pull requests.
___
Pull request protocol:
People can tag pull requests into three categories:
    - Small
        - typo, small bug edge case fix, added test cases, adding documentation, renaming
    - Medium
        - 
    - Large
        - new functionality, new dependency, 

(Small/Medium/Large) pull requests will require (1/2/3) people besides the person opening 
the PR to approve the PR.

There may also be need for things like entire project refactoring, or something that will 
make our pull-request method of development much more difficult. If you believe some significant 
change may be needed for the project, bring it up in #general or something