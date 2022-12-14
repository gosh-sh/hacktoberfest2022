![alt text](https://res.cloudinary.com/practicaldev/image/fetch/s--n6yDj0MN--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/12t9r8j7n9ynxbdzhs5p.png)

## Link
https://hacktoberfest.com/ 

# Welcome to Hacktoberfest 2022 Public Repository
Hacktoberfest is an annual event hosted by DigitalOcean. It encourages people to contribute to open source repositories throughout the month of October. Lots of modern tech infrastructure relies on open source projects built and maintained by passionate people who often don’t have the staff or budgets to do much more than keep the project alive. Hacktoberfest is all about giving back to those projects, sharpening skills, and celebrating all things open source, especially the people that make open source so special.

# Code of conduct
Please follow our [Code Of Conduct](https://app.gosh.sh/o/gosh/r/gosh/blobs/view/main/code_of_conduct.md) when contributing.

# What can You contribute 
We accept any plugins and integrations with gosh for any third party tools (project management, jenkins, etc.)
Please see issues for more details, but you are welcome to come up with your own ideas.

# How to Contribute to this repository
You can use our main [GOSH repository](https://github.com/gosh-sh/gosh) to make forks and find actual code.
Please send a [GitHub Pull Request to GOSH Hacktoberfest](https://github.com/gosh-sh/hacktoberfest2022) with a clear list of what you've done (read more about [pull requests](http://help.github.com/pull-requests/)). 
Please follow our coding conventions (below) and make sure all of your commits are atomic (one feature per commit).
Please make tests!

Always write a clear log message for your commits. One-line messages are fine for small changes, but bigger changes should look like this:

    $ git commit -m "A brief summary of the commit
    > 
    > A paragraph describing what changed and its impact."


## Coding conventions

We expect any server software to be written in [Rust](https://www.rust-lang.org/), whenever possible.
Please follow Rust official [style guide](https://github.com/rust-dev-tools/fmt-rfcs)


The front end should use [TypeScript](https://www.typescriptlang.org/), unless is native for some reason, like mobile.
Prettier with .prettierrc
```
{
    "semi": false,
    "tabWidth": 4,
    "trailingComma": "all",
    "singleQuote": true,
    "printWidth": 90
}
```
* Prefer the object spread operator ({...anotherObj}) to Object.assign()
* Place requires in the following order:
       - Built in modules
       - Installed packages
       - Local Modules
* Avoid platform-dependent code

# GOSH rewards
If on top of commiting to this repository you will also push your commits to the GOSH repository on GOSH, we will distribute some additional; rewards in the form of future GOSH Tokens as per: [GOSH DAO Contribution Guide](https://app.gosh.sh/o/gosh/r/gosh/blobs/view/main/GOSH_DAO_Contribution_Guide.md)



