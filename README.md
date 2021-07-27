# :diamond_shape_with_a_dot_inside: VRChat standard git project settings :diamond_shape_with_a_dot_inside:

Defines a standard git settings for VRChat avatar and world projects.

**No more losing any files we needed.**

## NOTE

This is still inexperienced because I don't have enought knowledge of Unity.

:gift: **PullRequests are welcome** :gift:

And don't forget `git lfs install`.  
I recommend [sh-git-lfs-install-append](https://github.com/aiya000/sh-git-lfs-install-append) if you already have your git hooks template.

## Contents

- `.gitignore`
    - The feature is that includes `/[Ll]ibrary/*`. This means include a lot of objects
        - But I couldn't restart VRChat projects by `git-clone` because necessary objects ware missing

- `.gitattributes`
    - VRChat (Unity) projects may contain a lot of media type files. This includes those
    - text type files are not included
        - Please tell for me either if this is including text type files or that is not including necessary media type files

## Tips
### Don't forget `git lfs pull` after you did `git-clone` your repository

Really...
