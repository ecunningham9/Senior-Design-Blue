# Team roster assignment

[Illustrated assignment handout (PDF)](team-roster-assignment.pdf)

You will add your GitHub username and correct your hometown in your team's roster. This gives you practice saving a file, recording a change with Git, and sharing it with your team.

Use your team's repository:

- **Blue:** [Senior-Design-Blue](https://github.com/mmurphy39-hash/Senior-Design-Blue)
- **Gold:** [Senior-Design-Gold-Test](https://github.com/BraxtonAlexander0/Senior-Design-Gold-Test)

 The instructor's tutorial repository is for the lecture demonstration. Your assignment belongs in your team's repository.

## Part 1: Install the app and get access

1. **Install GitHub Desktop on your computer.** Download it from [desktop.github.com](https://desktop.github.com/) and run the installer. Use your Windows or Mac laptop for this assignment.

2. **Create a GitHub account.** Go to [github.com/signup](https://github.com/signup). Choose a username and finish the account setup, including verifying your email address. If you already have an account, use it.

3. **Email your software coordinator.** Include your name, Blue or Gold team, role number, and GitHub username. Send the username you chose, not just your email address or display name. The coordinator uses it to give you permission to contribute to the team's repository. Do not send your password.

4. **Accept the invitation.** Your coordinator will invite your GitHub account to the team repository. Look for GitHub's invitation email, open its link, sign into the account from step 2, and accept. Check [GitHub notifications](https://github.com/notifications) if you cannot find the email. Ask the coordinator if no invitation appears. Sending your username alone does not finish the access setup.

5. **Sign into GitHub Desktop with that same account.** Open the app, choose **Sign in to GitHub.com**, and follow the browser prompts back to Desktop. If it asks you to configure Git, enter your name and choose the email associated with your GitHub account. If you skipped sign-in earlier, open **File → Options → Accounts** on Windows or **GitHub Desktop → Settings → Accounts** on Mac, then choose **Sign Into GitHub.com**.

All parts of this assignment can be completed after the guest lecture. After step 3, wait for your coordinator to invite you. Continue after you accept the invitation. The repository links are listed above.

## Part 2: Edit and share your roster entry

6. **Download your team's repository through GitHub Desktop.** This is called *cloning* and normally happens once on each computer. In Desktop, click **File → Clone Repository…**, then click the **URL** tab. Paste your team's repository link from the top of this prompt. The **Local Path** is the folder on your computer where the files will go. Leave the suggested path or choose a convenient folder. Click **Clone** and wait for it to finish. If you already cloned this same team repository, select it under **Current Repository** instead of cloning again.

7. **Select the `dev` branch.** At the top of Desktop, click **Current Branch**. Type **dev** in the filter box if needed, then click the existing **dev** entry in the list. The toolbar should now say **Current Branch: dev**. Selecting a branch is also called *checking it out*. It tells Git which version of the project files to put in your local folder. Use the existing `dev` branch, not **New Branch**. If `dev` is missing, click **Fetch origin**, check again, and ask the coordinator if it still does not appear.

8. **Get the latest team changes.** Click **Fetch origin** at the top of Desktop. If the button changes to **Pull origin**, click it. Fetch checks for new commits on GitHub. Pull brings those changes into your local copy. If Pull does not appear, you are already up to date.

9. **Open and edit the roster file on your computer.** In Desktop choose **Repository → Show in Explorer** on Windows or **Repository → Show in Finder** on Mac. Open **team-roster.txt** in a plain text editor such as Notepad on Windows or TextEdit on Mac. In TextEdit use **Format → Make Plain Text** if needed. Use a monospaced font and turn word wrapping off so you can see the aligned columns. Find your **role number**. In that row, fill the blank GitHub username column and replace the example hometown with your real hometown. Keep spaces between the columns and do not use Tab. Leave the role description, technical assignment, and other students' rows unchanged. Save the file with its existing name.

10. **Check what changed.** Return to Desktop and click **Changes**, then **team-roster.txt**. Red shows the old text and green shows the new text. Check that your username and hometown are correct and that you edited only your row. If you changed something else accidentally, correct it in the editor and save again before continuing.

11. **Record your change with a commit.** Check the box beside **team-roster.txt** to include it. In the **Summary** box at the lower left, type a message such as **Add username and hometown for role 7**, using your own role number. Click the blue commit button, whose label should end with **to dev**. This records your change on your computer. It has not been sent to the team yet. If the button label ends with **to main**, stop and ask the coordinator for help before committing.

12. **Send the commit to your team.** Click **Fetch origin** again. If **Pull origin** appears, click it first to receive changes other students have made. Then click **Push origin** to send your commit to GitHub. If GitHub says there are newer changes, repeat Fetch, Pull if offered, and Push. If Desktop reports a conflict, stop and ask your coordinator for help. If it offers to create a fork or reports that you do not have permission, ask the coordinator to check your invitation and access.

13. **Check that your update arrived.** In Desktop choose **Repository → View on GitHub**. On the website, use the branch dropdown above the file list to select **dev**, then open **team-roster.txt**. Confirm your username and hometown appear in your role's row. You are finished when your change is visible in the shared team's `dev` branch online, not just in the copy on your computer.

You do not need to create a fork, a new branch, or a pull request for this assignment. Use the existing `dev` branch and push directly to it. The software coordinator will review the team's changes and update `main`.

## If you get stuck

Tell the coordinator which step you reached and what Desktop says. Keep your saved file and local commit. Do not replace the entire roster with an older copy or try to fix a conflict by deleting someone else's row.

The supplied hometowns are fictional examples to replace. GitHub usernames start blank. Your team’s roster is already available as **team-roster.txt** on the **dev** branch.

## References

- [Cloning a repository in GitHub Desktop](https://docs.github.com/en/desktop/adding-and-cloning-repositories/cloning-and-forking-repositories-from-github-desktop)
- [Selecting a branch in GitHub Desktop](https://docs.github.com/en/desktop/making-changes-in-a-branch/managing-branches-in-github-desktop)
- [Signing into GitHub Desktop](https://docs.github.com/en/desktop/installing-and-authenticating-to-github-desktop/authenticating-to-github-in-github-desktop)
