# thesis-template
A Latex Template for your bachelor / master thesis

Please note: This is only a template. You have to adapt the template to your thesis and discuss the structure of your thesis with your supervisor

> There is also a GitHub workflow in this template, that automatically builds the LaTeX document and creates a release with the built PDF.
>
> To use the workflow with an existing fork of the repository, simply apply the changes to your fork like this:
>
> ```bash
> # Move into your repository
> cd <REPOSITORY>
>
> # Get the changes and apply them
> curl -L https://github.com/ls1intum/thesis-template/pull/12/commits/0679ed5d48e361edf2866b02f39832e6552d0033.patch | git apply
> git add .github/workflows/build-release-thesis.yml
> git commit -m "Add workflow for automatic LaTeX builds."
> 
> # (Optional) Push the changes
> git push
> ```
