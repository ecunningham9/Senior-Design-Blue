# Software coordinator setup

The roster assignment files are ready on `dev`. Students complete the assignment after the guest lecture and push their own row changes directly to `dev`.

## Protect main before students contribute

You own this personal-account repository. The instructor's collaborator account can publish files and branches, but you must configure the repository rules and invite students.

1. Open this repository on GitHub and choose **Settings → Rules → Rulesets**. The sidebar may show **Rulesets** directly.
2. Choose **New ruleset → New branch ruleset**.
3. Name it **Protect main** and set enforcement to **Active**.
4. Under **Target branches**, add the exact branch name **main**. Use the exact name rather than the default-branch target, especially if you later make `dev` the default branch.
5. Enable **Restrict updates**, **Restrict deletions**, and **Block force pushes**.
6. Under **Bypass list**, add **Repository admin** with **Always allow**. This allows you, the repository owner, to push reviewed changes to `main`. Do not add the Write role, which would let all student collaborators bypass the restriction.
7. Leave **Require a pull request before merging** off. Save the ruleset.
8. Leave `dev` available for ordinary collaborator pushes. Students do not need pull requests.
9. Optionally make **dev** the default branch under **Settings → General → Default branch** to make the assignment easier to find. The student instructions explicitly select `dev` either way.
10. Verify that an ordinary collaborator can push to `dev` but cannot push to `main`. Verify that your owner account can push reviewed changes to `main`.

Until the rule is active, the branch names alone do not prevent students from pushing to `main`.

## Give students access after the lecture

1. Students email you their name, team, role number, and GitHub username.
2. Open **Settings → Collaborators → Add people** and invite each student's exact username.
3. Ask the student to accept the invitation while signed into that account, then sign into GitHub Desktop with the same account.
4. Point students to **STUDENT-INSTRUCTIONS.md** and **team-roster-assignment.pdf** in this repository's `dev` branch.
5. Help with any roster merge conflict by keeping both students' completed rows. Do not replace the shared roster with an older whole-file copy.

## Review dev and update main

1. In GitHub Desktop select this team's repository and **Current Branch → dev**.
2. Click **Fetch origin**, then **Pull origin** if offered. Review contributions in **History**. For robot code later in the project, run and test it before approving it.
3. Select **Current Branch → main** and Fetch/Pull any updates.
4. Choose **Branch → Merge into current branch**, select **dev**, and complete the merge.
5. Inspect the result, then **Push origin** using your permitted owner account.
6. Keep `dev` for continued development. If you ever make a fix directly on `main`, merge it back into `dev` before development continues.

This first reviewed merge also brings the initial assignment files from `dev` into `main`.

## GitHub references

- [Personal repository permissions](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/repository-access-and-collaboration/permission-levels-for-a-personal-account-repository)
- [Create a branch ruleset](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets/creating-rulesets-for-a-repository)
- [Restrict updates](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets/available-rules-for-rulesets#restrict-updates)
