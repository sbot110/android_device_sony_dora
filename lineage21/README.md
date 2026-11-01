# Sony Xperia X Performance (dora) - LineageOS 21 development snapshot

The Sony device trees and kernel are published in the `Lineageos-21` branches
of the corresponding sbot110 GitHub repositories. Upstream LineageOS/AOSP
projects are not duplicated here; their base source is restored by `repo`.

`repo-manifest-base.xml` is a snapshot of the original local checked-out HEADs.
The accompanying `patches/*.worktree.patch` capture staged, unstaged, AND
untracked non-ignored additions from modified upstream projects, relative to
those HEADs. The optional `*.local-commits.patch` captures unpublished local
commits separately; apply it before the matching worktree patch.

This is an Android 14 bring-up/development snapshot, not a final stable build.
