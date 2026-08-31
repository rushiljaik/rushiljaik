# Set up your interactive GitHub profile

This package is a GitHub-native profile README. It avoids JavaScript because GitHub strips scripts from Markdown, while still providing animation, clickable navigation, expandable sections, live statistics, theme-aware graphics, and an automatically updated contribution snake.

## 1. Personalize it

The package is already personalized for **Rushil Jai Krishan Pandita** at `github.com/rushiljaik`, using the current public repositories and technology stack. Review the bio and project descriptions in `README.md`; edit anything you would like to phrase differently.

Open `assets/hero.svg` if you want to change the displayed name, tagline, or colors.

## 2. Create the special profile repository

On GitHub, create a **public** repository named **`rushiljaik`**. The full repository path must be `rushiljaik/rushiljaik`; a repository named `git` will not appear as your special profile README.

Copy these items into the repository root:

```text
README.md
assets/
.github/
```

Commit and push them to the `main` branch.

## 3. Start the contribution animation

Open the repository's **Actions** tab, select **Generate contribution snake**, and choose **Run workflow**. The workflow will create an `output` branch containing both light and dark animations. It then refreshes them daily.

If GitHub initially disables workflows in the new repository, enable Actions when prompted. The workflow only needs permission to write generated SVG files to the same repository.

## 4. Check every link

Visit your GitHub profile and verify the project cards, repository links, live statistics, and animated contribution graph. Live statistic cards may take a little time to refresh.

## Easy customizations

- Change the gradient colors in `assets/hero.svg` by editing `#7C3AED` and `#06B6D4`.
- Choose different skill icons at <https://skillicons.dev>.
- Create badge styles at <https://shields.io>.
- Remove any section you do not want; the navigation links should be updated to match.
