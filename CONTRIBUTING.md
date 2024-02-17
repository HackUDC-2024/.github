This section guides you through submitting an enhancement suggestion for UnPlug, **including completely new features and minor improvements to existing functionality**. Following these guidelines will help maintainers and the community to understand your suggestion and find related suggestions.

#### Before Submitting an Enhancement

- Make sure that you are using the latest version.
- Perform a [search](http://gihtub.com/hackudc-unplug/issues) to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.
- Find out whether your idea fits with the scope and aims of the project. It's up to you to make a strong case to convince the project's developers of the merits of this feature. Keep in mind that we want features that will be useful to the majority of our users and not just a small subset. If you're just targeting a minority of users, consider writing an add-on/plugin library.

#### How Do I Submit a Good Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](http://gihtub.com/hackudc-unplug/issues).

- Use a **clear and descriptive title** for the issue to identify the suggestion.
- Provide a **step-by-step description of the suggested enhancement** in as many details as possible.
- **Describe the current behavior** and **explain which behavior you expected to see instead** and why. At this point you can also tell which alternatives do not work for you.
- You may want to **include screenshots and animated GIFs** which help you demonstrate the steps or point out the part which the suggestion is related to. You can use [this tool](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast).
- **Explain why this enhancement would be useful** to most UnPlug users. You may also want to point out the other projects that solved it better and which could serve as inspiration.

### Your First Code Contribution
#### Backend
```bash
git clone https:github.com/unplug/backend.git
cd backend
# Setup poetry and add it to your PATH
# It is recommended to make poetry create the virtualenvs in your project
# poetry config virtualenvs.in-project true
poetry install --no-root
poetry run pre-commit install
poetry run pre-commit autoupdate
```
#### Frontend
```bash
git clone https:github.com/unplug/frontend.git

```

## Styleguides
### Commit Messages
We follow the [Angular commit convention is](https://www.conventionalcommits.org/en/v1.0.0/)
