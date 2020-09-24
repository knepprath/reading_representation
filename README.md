# Reading Representation

A static site built with Hugo using the Osprey Delight theme

This project uses a git submodule to pull in the theme. When cloning this repo use:
`git clone --recursive`

To run locally:
`hugo server -D`

To deploy:
1. Configure AWS CLI
2. Build static site `hugo -D`
3. `hugo deploy`
