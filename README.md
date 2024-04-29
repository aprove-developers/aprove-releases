# aprove-releases
Contains publicly available releases of AProVE.

To create a new release, create an empty commit and use the git-sha of the respective commit in the aprove-repository as commit message (`git commit --allow-empty -m "$SHA"`).
Then, tag (`git tag $TAG`) and push the commit and the tag (`git push origin $TAG`).

For competiton versions, use tags like `termcomp16` resp. `svcomp16`.
For all other versions, please use tags like `master-2016-09-19`.
If you are releasing a version of a feature branch,
please prefix the tag with the name of the feature branch to avoid confusion with "official" releases (e.g., `jbc-complexity_2016_09_19`).

Then, you can associate a release with your tag.
To do so, click `<> Code` and then `releases`.
