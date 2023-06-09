# Purpose
This repository triggers a pipeline that copies its contents
to [](https://schemas.ndumas.com). I've set it up this way
exclusively because I was too lazy to figure out how to write
Go code that could resolve local/relative references to other
JSONSchema files.

It ends up being a hell of a lot simpler to just host them
online and use absolute references.


# Collaboration
To that end, I am opening this repository to PRs. Pretty much
anything reasonable is on the table, if you're gonna use it.

# Caveat
This repository will not teach you what JSONSChema is or
how to use it, althought it does contain some practical
examples.

I'd strongly recommend working through the [official documentation](https://json-schema.org/learn/getting-started-step-by-step.html)
to get a grasp on things.
